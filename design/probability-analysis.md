# Probability Analysis

Probability analysis for the 2d10 Engine. Mathematical findings only. This is not a balance assessment and not a playtest result.

## 2d10 sum distribution

Two ten-sided dice (1–10 each) give 100 equally likely outcomes. Sums range from 2 to 20, average 11.

| Sum | Ways | P(exactly) | P(≤ sum) | P(≥ sum) |
| --: | --: | --: | --: | --: |
| 2 | 1 | 1% | 1% | 100% |
| 3 | 2 | 2% | 3% | 99% |
| 4 | 3 | 3% | 6% | 97% |
| 5 | 4 | 4% | 10% | 94% |
| 6 | 5 | 5% | 15% | 90% |
| 7 | 6 | 6% | 21% | 85% |
| 8 | 7 | 7% | 28% | 79% |
| 9 | 8 | 8% | 36% | 72% |
| 10 | 9 | 9% | 45% | 64% |
| 11 | 10 | 10% | 55% | 55% |
| 12 | 9 | 9% | 64% | 45% |
| 13 | 8 | 8% | 72% | 36% |
| 14 | 7 | 7% | 79% | 28% |
| 15 | 6 | 6% | 85% | 21% |
| 16 | 5 | 5% | 90% | 15% |
| 17 | 4 | 4% | 94% | 10% |
| 18 | 3 | 3% | 97% | 6% |
| 19 | 2 | 2% | 99% | 3% |
| 20 | 1 | 1% | 100% | 1% |

## Doubles

- Any doubles: 10 of 100 = **10%**.
- Double ones: **1%**. Double tens (natural 20): **1%**.
- Tagged Skill automatic success (doubles except double ones, per the glossary): **9%**, independent of DC.

## Relevance

These tables support [UQ-0001](unresolved-questions.md#uq-0001--check-roll-direction). Under roll-under-or-equal, the chance of success is the P(≤ sum) column at the DC. Under meet-or-exceed, it is the P(≥ sum) column. Because the DC is built from the acting character's own ratings, the two readings move in opposite directions as ratings rise.

Advantage and Disadvantage (roll an extra die, keep the best or worst) are not analyzed yet, because which dice are kept depends on UQ-0001.
