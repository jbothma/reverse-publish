# reverse-publish
NB: Idea phase - Project for extracting structured text from a document in a "published" form, e.g. PDF or scan image (and OCR'd text)

## Problem

OCR of a scan of a printed document is often not sufficient for extracting the text correctly. Even the Adobe Paper Capture Plugin doesn't recognise multi-column text. When the PDF text is extracted, lines read across columns.

The structure of the document is also lost. E.g. the transcript at http://docslide.us/business/south-africa-national-development-plan-vision-2030-executive-summary.html seems to have a good extraction of the text, but page breaks ans headers and footers interrupt normal flow of the text.

## Ideas

### Longest repeating substring

Should help identify header/footers which can then be pulled out from the normal text flow
