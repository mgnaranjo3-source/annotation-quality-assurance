# Gold-Set Audit Summary

Source: [`data/gold-set-audit.csv`](data/gold-set-audit.csv), 15 gold items, 3 annotators, 5 items each.

## Accuracy per annotator
| Annotator | Correct | Total | Accuracy |
|---|---|---|---|
| ann_A | 4 | 5 | 80% |
| ann_B | 3 | 5 | 60% |
| ann_C | 4 | 5 | 80% |
| **All** | **11** | **15** | **73%** |

## Errors by type
| Code | Type | Count | Annotators |
|---|---|---|---|
| E2 | Boundary miss | 2 | ann_A, ann_B |
| E3 | Sarcasm miss | 2 | ann_B, ann_C |

## Actions
1. **Sarcasm (E3) appears across two annotators**, so this is a guideline/training issue, not an individual one. Add three more sarcasm examples (EN and ES) to the guideline and include sarcasm items in the next calibration session.
2. **Boundary misses (E2)** relate to rules added in v1.1. Send a short changelog note to all annotators highlighting the new boundary examples.
3. **ann_B** has two errors out of five: send individual feedback (see templates) and re-audit on the next batch before drawing conclusions from such a small sample.
