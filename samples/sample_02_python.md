# Sample 02: Python Code Evaluation

## Prompt

Write a Python function that returns the factorial of a non-negative integer.

## Response A

```python
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n - 1)
```

## Response B

```python
def factorial(n):
    return n
```

## Evaluation

**Winner:** Response A

## Scores

| Criterion | Response A | Response B |
|---|---:|---:|
| Instruction Following | 4 | 2 |
| Accuracy | 4 | 1 |
| Completeness | 3 | 1 |
| Clarity | 4 | 4 |
| Reasoning Quality | 4 | 1 |

## Explanation

Response A correctly implements a recursive factorial function and includes the base case for `n == 0`. It does not handle negative inputs, so it is not perfect, but it satisfies the core requirement.

Response B is incorrect because it simply returns the input number and does not calculate the factorial.
