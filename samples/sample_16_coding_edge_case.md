# Sample 16: Coding Edge Case

## Prompt

Write a Python function to return the maximum number in a list. Mention how empty lists should be handled.

## Response A

`max(numbers)` returns the maximum, but an empty list should be checked first to avoid an error.

## Response B

`max(numbers)` works for all lists, including empty lists.

## Evaluation

**Winner:** Response A

## Scores

| Criterion | Response A | Response B |
|---|---:|---:|
| Instruction Following | 5 | 2 |
| Accuracy | 5 | 2 |
| Completeness | 5 | 2 |
| Clarity | 5 | 2 |
| Reasoning / Quality | 5 | 2 |

## Explanation

Response A identifies the important empty-list edge case. Response B is incorrect because `max([])` raises an error.
