# Sample 04: Math Reasoning

## Prompt

What is the coefficient of a²b²c² in the expansion of (a + b + c)^6?

## Response A

The coefficient is 90 because we choose positions for two a's, two b's, and two c's:
6! / (2!2!2!) = 90.

## Response B

The coefficient is 720 because 6! = 720.

## Evaluation

**Winner:** Response A

## Scores

| Criterion | Response A | Response B |
|---|---:|---:|
| Instruction Following | 5 | 3 |
| Accuracy | 5 | 1 |
| Completeness | 5 | 2 |
| Clarity | 5 | 3 |
| Reasoning Quality | 5 | 1 |

## Explanation

Response A is correct because it uses the multinomial coefficient formula. The coefficient of a²b²c² is:

```text
6! / (2! 2! 2!) = 720 / 8 = 90
```

Response B incorrectly gives 6! without dividing by the repeated factorial terms.
