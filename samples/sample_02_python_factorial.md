# Sample 02: Python Factorial

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
| Instruction Following | 5 | 2 |
| Accuracy | 5 | 2 |
| Completeness | 5 | 2 |
| Clarity | 5 | 2 |
| Reasoning / Quality | 5 | 2 |

## Explanation

Response A implements the factorial logic correctly for non-negative integers. Response B simply returns the input and does not compute a factorial.
