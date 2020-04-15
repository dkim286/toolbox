# `office/`

Contains all the document-related scripts.

## Dependencies

* pandoc
* pdflatex

## Scripts

### `makepdf`

Use pandoc to convert a text-based document to PDF. 

Primarily geared towards converting Markdown files, but other filetypes also work to some degree.

Example:

```
$ makepdf class-notes.md
$ ls
class-notes.md  class-notes.pdf
```
