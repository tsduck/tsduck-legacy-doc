## Legacy documentation

### Documentation files

This directory contains legacy documentation files, essentially
the TSDuck user's guide and coding guidelines, is Microsoft Word
and PDF format.

### Font files

The files `gadugi.ttf` and `gadugib.ttf` contain the Gadugi true-type font,
used in the documents.

### Scripts

The PowerShell script `build-user-guide-pdf.ps1` was used to update `tsduck.docx`
and generate `tsduck.pdf` from `tsduck.docx`.

It updated the TSDuck version, current month, table of contents, etc. The idea
was to manually update `tsduck.docx` with new content using Word, then exit and
run `build-user-guide-pdf.ps1` to update the structure and version of the document.

This script is kept here for reference only.
