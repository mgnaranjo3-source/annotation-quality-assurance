# Reviewer QA Checklist

## Before reviewing
- [ ] I have the **current** guideline version open
- [ ] I know which edge-case decisions were added this week

## For every item
- [ ] Label is from the allowed label set (no typos, no deprecated labels)
- [ ] Label matches the guideline's **decision order**, not just my intuition
- [ ] Required fields are filled (label, confidence/unsure flag, comment if required)
- [ ] Comments are specific and in the required language
- [ ] No personal data was copied into comments
- [ ] For AI-response ratings: scores respect the **hard caps** (factual error, safety)
- [ ] For AI-response ratings: rationale names the deciding factor and quotes the text

## For the batch
- [ ] Label distribution looks plausible (e.g., not 95% one class unless expected)
- [ ] No duplicated items with conflicting labels
- [ ] Time per item is reasonable (very fast items get a second look)
- [ ] New edge cases are logged for the guideline owner
