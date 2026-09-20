---
name: college-word-docs
description: Create, reformat, or audit Word documents for college using established page, paragraph, heading, table, listing, image, caption, and pagination rules. Use for .docx reports, laboratory work, practical work, essays, and similar college submissions; explicit assignment or template requirements override these defaults.
---

# College Word Docs

Apply the rules in [references/formatting-rules.md](references/formatting-rules.md) whenever creating, correcting, or checking a Word document.

## Working principles

- Treat the user's assignment, methodical guide, template, and explicit corrections as higher priority than the defaults. Ask only when applicable requirements conflict and the result cannot be inferred.
- Preserve wording, images, tables, code, numbering, and structure unless the user also requests content changes.
- Distinguish main headings, subheadings, ordinary paragraphs, table contents, captions, images, and code listings by function rather than unreliable existing styles alone.
- Apply formatting through Word paragraph, character, section, table, and style properties. Do not imitate indents with spaces. Set a 1.75 cm tab stop instead of inserting a tab at the start of every paragraph.
- Preserve a supplied title-page or department template. Count the title page but do not display its page number.

## Workflow

1. Inspect the source document and any assignment or template.
2. Classify elements and record requirements that override the defaults.
3. Apply the reference rules consistently, including styles and direct formatting that could override them.
4. Render the completed document to PDF or page images and inspect every page. Fix premature listing splits, separated captions, clipped objects, unexpected blank space, and visible numbering on the title page.
5. Recheck paper size, margins, fonts, sizes, paragraph spacing, line spacing, alignment, first-line indents, tab stops, captions, table pagination, and footer numbering programmatically where possible.
6. Deliver the corrected `.docx` and summarize only material decisions or unresolved conflicts.

## Pagination safeguards

- Keep an image with its following caption and a table or listing caption with the first row of its object.
- Do not split a listing early. Fill the available page space, then continue only when the current page is actually full.
- For a multi-page listing, use a separate one-cell table for each page segment and repeat its caption above every segment. Prevent one listing cell from splitting across pages.
- Do not add manual page breaks unless required by the document structure or a stable, verified layout.
