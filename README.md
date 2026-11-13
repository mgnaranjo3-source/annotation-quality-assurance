# Annotation Quality Assurance Playbook

How to review annotated data before it reaches a model: a QA checklist, a gold-set audit, an error taxonomy, and templates for giving annotators feedback that actually helps.

> The audit data in this repo is **synthetic** and created for demonstration.

## Contents
| File | Purpose |
|---|---|
| [`qa-checklist.md`](qa-checklist.md) | What a reviewer checks on every task |
| [`error-taxonomy.md`](error-taxonomy.md) | Common annotation errors, grouped by type and severity |
| [`data/gold-set-audit.csv`](data/gold-set-audit.csv) | Synthetic audit of 15 items against gold labels |
| [`audit-summary.md`](audit-summary.md) | Accuracy per annotator and per error type from that audit |
| [`feedback-templates.md`](feedback-templates.md) | Clear, specific, respectful reviewer feedback examples |

## QA workflow
1. **Gold items:** mix pre-labeled "gold" items into the queue, unseen by annotators.
2. **Audit:** compare annotator labels to gold; tag each error with a type from the taxonomy.
3. **Summarize:** accuracy per annotator and per error type.
4. **Act:** guideline fix if many annotators miss the same thing; individual feedback if one does.
5. **Re-check:** audit the next batch to confirm the fix worked.

## License
MIT
