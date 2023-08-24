## 📒 Changelog

### of [ADBT](https://github.com/igorskyflyer/vscode-adbt)

<br>

## v1.3.0 _(25-Aug-2023)_

#### [ADBT v1.3.0](https://github.com/igorskyflyer/file-format-adbt/releases/tag/v1.3.0)

- **🪅 feat**: implement Actions for **`include`** and **`import`** statements

> 💡Actions allow you to invoke a certain function when including/importing filter list files.
>
> Supported actions:
>
> - trim (trims whitespace for each line from the included filter list file)
> - dedupe (removes duplicates from the included filter list file)
> - sort (sorts lines from the included filter list file)
> - append (appends an arbitrary string to each line from the included filter list file)
> - strip (strips a certain element of each line from the included filter list file)

<br>

## v1.2.0 _(20-Aug-2023)_

#### [ADBT v1.2.0](https://github.com/igorskyflyer/file-format-adbt/releases/tag/v1.2.0)

- **🪅 feat**: implement the **[`import`](https://github.com/igorskyflyer/file-format-adbt/blob/v1.2.0/README.md#import)** statement
  > **`import`** statements behave exactly the same as **`include`** but prepend the file path of the included filter (as a comment)
- **🪅 feat**: implement the **[`tag`](https://github.com/igorskyflyer/file-format-adbt/blob/v1.2.0/README.md#tag)** statement
  > Introduce a tagging system; special comments that get inserted in the resulting filter file, for easier navigation, search, etc.

<br>

## v1.1.0 _(19-Aug-2023)_

#### [ADBT v1.1.0](https://github.com/igorskyflyer/file-format-adbt/releases/tag/v1.1.0)

- **🪅 feat**: support for Expires field in meta files

<br>

## v1.0.5 _(03-Aug-2023)_

- **🪅 feat**: add directives support
- **🪅 feat**: add more snippets
- **🪅 feat**: enable trigger characters

<br>

## v1.0.4 _(30-Jul-2023)_

- **✅ fix**: rework syntax highlighting,
- **✅ fix**: fix hover provider bug

<br>

## v1.0.3 _(28-Jul-2023)_

- **🪅 feat**: add JSON association for `*.adbm` files,
- **✅ fix**: improve `*.adbm` meta files Intellisense,
- **✅ fix**: fix README links

<br>
<br>

## v1.0.2 _(27-Jul-2023)_

- **🪅 feat**: add file type icon

<br>
<br>

## v1.0.1 _(27-Jul-2023)_

- **✅ fix**: fix galleryBanner on Marketplace

<br>
<br>

## v1.0.0 _(27-Jul-2023)_

- **🚀 launch**: initial release 🎉
