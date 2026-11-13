# Annotation Error Taxonomy

| Code | Error type | Description | Typical cause | Severity |
|---|---|---|---|---|
| E1 | Wrong label | Clear guideline violation | Rushing, misreading | Major |
| E2 | Boundary miss | Wrong side of a documented boundary case | Guideline not memorized | Minor–Major |
| E3 | Sarcasm / irony miss | Labeled literal instead of intended meaning | Ambiguous text | Major |
| E4 | Overuse of "unsure" | Unsure flag on items the guideline clearly covers | Low confidence, unclear training | Minor |
| E5 | Missing field | Required comment, span or flag left empty | Tool or attention issue | Minor |
| E6 | Rationale too vague | AI-rating justification not specific or not quoted | Writing habit | Minor |
| E7 | Cap not applied | Factual or safety issue found but score not capped | Rubric not followed | Critical |
| E8 | Outside knowledge | Used personal knowledge the guideline excludes | Guideline scope unclear | Minor |

**Severity guide:** *Critical* = data would actively teach the model wrong behavior; *Major* = wrong label; *Minor* = label right or defensible but process not followed.
