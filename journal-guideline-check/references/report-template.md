# Report Template: guideline-check-report.md

Used in Phase 4. Write the report using this structure.

```markdown
# Journal Guideline Compliance Report

- **Manuscript**: <filename / project directory / PDF>
- **Journal guideline**: <guideline filename or URL> (<journal name, if known>)
- **Guideline source and snapshot**: <for a local file, its path; for a URL, the fetch time + raw HTML/PDF snapshot path>
- **Check date**: <YYYY-MM-DD>
- **Summary**: ✅ X compliant | ❌ Y non-compliant | ⚠️ Z undeterminable (checklist verdicts only; notes are counted separately below)

---

## ❌ Non-Compliant (needs action)

### 1. <Category>: <one-line issue>
- **Guideline requirement** (original): "<exact sentence from the guideline>" (source: <page / section heading / line>)
- **Manuscript state**: <objective description, with actual figures>
- **Location**: <mark the source and position per principle 3>
- **Severity**: 🔴 mandatory / 🟠 recommended

(list every ❌ item)

---

## ⚠️ Undeterminable (needs your confirmation)

### 1. <Category>: <issue>
- **Reason**: <not mentioned in the guideline / ambiguous clause / input format limitation (e.g. md cannot reveal layout, PDF has no text layer, web content behind a collapsed panel)>
- **Guideline wording** (if any): "..."
- **What we need from you**: <specific question>

---

## Notes (not judged)

<List, one by one, desk-rejection categories the guideline does not cover and clauses whose conditions do not apply, with the reason each was left unjudged>

---

## ✅ Compliant (list)

| Category | Check item | Guideline requirement | Manuscript state |
|---|---|---|---|
| <Category> | <Check item> | <Requirement> | <State> |

(one table, no elaboration)

---

## Appendix: Full Checklist Extracted for This Check

<All clauses extracted from the guideline, grouped by category, each with its original wording, so the user can verify that nothing was missed>
```

## Writing Rules

1. Write the report in English; keep quoted guideline wording in its original language.
2. Numeric comparison example: requirement "≤ 8,000 words", state "full text 9,214 words, including references".
