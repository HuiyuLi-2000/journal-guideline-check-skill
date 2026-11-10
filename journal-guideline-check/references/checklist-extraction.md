# Checklist Extraction Rules: Identifying Requirements in a Guideline

Used in Phase 1. Goal: turn the full guideline into a structured checklist where each item has [original wording / category / required value / severity / determinability].

## 1. Severity Signal Words

### 🔴 Mandatory (non-compliance can mean desk rejection)

- Modal verbs: must, shall, required, mandatory, will not be considered, will be rejected, will be returned
- Quantified caps: must not exceed, no more than, maximum, limit of, up to, restricted to
- Explicit instructions: must be submitted as, must be anonymized/blinded, must include, is required to
- Unconditional normative statements: Manuscripts are double-spaced. / Figures must be... / The abstract should not exceed (note: should + not exceed + a specific number is normally treated as mandatory; note "original uses should")

### 🟠 Recommended (no desk rejection, but affects impression)

- should (without a quantified constraint), recommended, encouraged, preferred, we advise, it is advisable

### Handling

- A mandatory signal word plus a specific number in one clause → 🔴; extract the figure exactly ("8,000 words" must not become "about 8,000 words")
- Vague phrasing (appropriate length, reasonable number) → extract but mark ⚠️ undeterminable and ask the user to confirm the basis

## 2. Common Clause Patterns (English guidelines)

| Pattern | Example | Extract as |
|---|---|---|
| Length cap | "Manuscripts should not exceed 10,000 words including references" | Full text ≤ 10,000 words (including references; mind the basis) |
| Page cap | "no longer than 25 pages, double-spaced" | ≤ 25 pages + double spacing |
| Abstract limit | "abstract of no more than 200 words" | Abstract ≤ 200 words |
| Structured abstract | "structured abstract with headings: Purpose, Methods, Results, Conclusions" | Abstract must contain the specified subsections |
| Keywords | "4–6 keywords" | 4–6 keywords |
| Required content | "must include a Highlights section / Statement of Ethics / Data Availability Statement" | The corresponding section must exist |
| Blind review | "double-blind: remove all identifying information" / "submitted in anonymized form" | Full anonymization check |
| Citation style | "APA 7th edition" / "numbered in order of appearance (Vancouver)" | Reference style |
| Reference count | "no more than 50 references" | ≤ 50 references |
| Figures and tables | "maximum of 6 tables and figures combined" / "figures at least 300 dpi" | Count cap / resolution |
| Layout | "double-spaced, 12-point Times New Roman, 1-inch margins" | Line spacing / font / margins |
| File rules | "submit as a single Word file named..." | Submission format and filename |

## 3. Extraction Notes

1. **Mind the counting basis**: Does a word limit include references, figure captions, or appendices? Quote the guideline if it says; otherwise mark ⚠️.
2. **Split compound clauses**: "no longer than 25 pages, double-spaced, 12-point font" is one sentence in the original but becomes three checkable items (pages / line spacing / font) citing the same passage.
3. **Do not miss implicit requirements**: cover letter, highlights, ethics statement, conflict of interest, data availability. When the guideline mentions one, check that the material exists.
4. **Spot conditional requirements**: "if your paper reports human subjects research, include an ethics statement". Ask the user whether the condition holds.
5. **Keep the original wording**: every checklist item must carry the guideline's exact sentence for comparison in the report. Do not substitute your own paraphrase.
6. **Extraction order**: work through the guideline in its original order, then group by category, so nothing is missed.

## 4. Extracting from Web Pages and PDFs

Applies when the guideline is a URL or a PDF. The original-wording and severity rules are unchanged.

1. Cite the plain-text copy saved in Phase 0; use the raw HTML / PDF snapshot to verify. Do not cite a fetch tool's summarized paraphrase.
2. Strip page noise: navigation, cookie banners, sidebars, headers, footers, page numbers, repeated section labels. This text does not enter the checklist.
3. Merge two-column PDF text blocks in reading order so left/right interleaving does not splice two requirements into one sentence.
4. When a guideline spans several pages or subpages, attach a source location (page number or section heading) to every checklist item.
5. Collapsed panels, script-rendered content, and login-gated blocks are ⚠️ undeterminable; state the reason and do not infer their content.
