# About

A collection of simple browser-based utilities written in HTML/JavaScript. Many generated with LLMs.

Credit to [https://github.com/simonw/tools](https://github.com/simonw/tools) ([https://tools.simonwillison.net/](https://tools.simonwillison.net/)) for the inspiration.

Some of these tools have command-line versions in [mbafford/cli-tools](https://github.com/mbafford/cli-tools).

# Tools

- [Image/Text to ICS (Calendar) Entry](image-to-ics) - Take an image (or text block) and extract an ICS file for adding to your calendar.  Screenshot a hotel reservation and let the LLM do the work of setting up dates/times/timezones/descriptions/etc.
- [Table Formatter](table-formatter) - Takes copy-and-paste of CSV, TSV, Markdown, table, or Google Sheets, and extracts the table and provides an easy copy to a multi-mime-type clipboard entry that can be pasted to Google Sheets, an email program as formatted email, or a text box as Markdown.
- [Loan Refinance Calculator](loan-refinance) - Refinance calculator - either enter terms manually, or paste in the details and it'll try to figure out the terms. Very US presumptive.
- [JWT Decoder](jwt-decode) - JWT decoder. Paste into browser. Similar to JWT.io, but in my control.
- [Base64 Image Decoder](base64-image) - Paste in a base64 image file and decode and display it in your browser. Also supports PDFs using pdf.js.
- [Date Difference Calculator](date-calculator) - Calculate number of days / weeks / years between two dates
- [Summarize JSON](summarize-json) - Summarize a complicated JSON object/array, showing the structure, data types, and sample values
- [JSON Comparison](json-analyzer-comparison) - Similar to Summarize JSON, but compares two sets of JSON to identify differences
- [ASCII Checker](ascii-checker) - Identify non-ASCII characters in pasted input
- [Epoch Time / Timestamps](epoch) - Convert epoch time to ISO8601/RFC3339 and human-readable format and vice versa
- [Dates to Calendar](dates2cal) - Paste in dates and see them represented on a calendar

# External Tools

- [Clipboard Viewer - Simon Willison](https://tools.simonwillison.net/clipboard-viewer) - See and extract the multiple entries stored in your clipboard.
