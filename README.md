# journal-guideline-check

An Agent Skill that checks a manuscript against a specific journal's author guidelines and writes a compliance report. It catches gaps that get a paper desk-rejected before review.

## What it does

Give it a manuscript and the journal's own guidelines. It reads the guideline in full, turns every requirement into a checkable item, collects the matching facts from the manuscript, and judges each item as ✅ compliant, ❌ non-compliant, or ⚠️ undeterminable.

Three rules hold throughout:

- Every check item comes from a sentence in the guideline. Requirements the guideline never mentions are not invented. Common desk-rejection categories the guideline omits appear only as notes in the report.
- Mandatory (🔴) and recommended (🟠) requirements are judged separately, so a suggested template is never reported as a submission blocker.
- The only deliverable is a report. The skill never edits the manuscript. Revising it is a separate step you approve.

Ambiguous clauses are quoted with their plausible readings and left for you to decide. Anything that cannot be determined goes into one confirmation list at the end.

## Supported inputs

| | Formats |
|---|---|
| Manuscript | a single Markdown file or a LaTeX file (recommended), a LaTeX project directory(recommended), or a PDF |
| Author guidelines | a local Markdown file (recommended), a local PDF file, or a web URL |

Markdown and LaTeX sources are read as they are and keep their structure. PDFs contribute a text layer plus page measurements (page count, fonts, line spacing, columns, image DPI). Web guidelines are snapshotted with their URL and fetch time so every quoted clause stays traceable.

## The report

A `guideline-check-report.md` written to the manuscript's directory:

- non-compliant items, each with the guideline's original wording, the manuscript's current state with actual figures, and an exact location
- undeterminable items with the reason and the question needed from you
- notes for categories the guideline does not cover
- a compact table of compliant items
- the full extracted checklist as an appendix, so you can spot anything the check missed

In conversation you get only the ❌ and ⚠️ summaries.

## Scope

This skill checks compliance against guidelines you supply. It does not select journals, run a generic pre-submission check without a specific guideline, or rewrite the manuscript.

## License

MIT.
