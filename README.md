# Day-93-Count-Positive-Negative-Zero
# Python Day 93 - Count Positive, Negative and Zero

This program counts the total number of positive numbers, negative numbers, and zeros in a list.

## Example

Input:

```text
[10, -5, 0, 25, -8, 0, 15]
```

Output:

```text
Positive numbers: 3
Negative numbers: 2
Zeros: 2
```

## Concepts Used

* Lists
* `for` loop
* `if-elif-else`
* Comparison operators
* Counter variables
* `+= 1`

## How It Works

1. Store numbers in a list.
2. Use a `for` loop to check each number.
3. If the number is greater than 0, increase the positive counter.
4. If the number is less than 0, increase the negative counter.
5. Otherwise, increase the zero counter.
6. Print the final counts.

## Python Code

```python
numbers = [10, -5, 0, 25, -8, 0, 15]

positive = 0
negative = 0
zero = 0

for number in numbers:
    if number > 0:
        positive += 1
    elif number < 0:
        negative += 1
    else:
        zero += 1

print("Positive numbers:", positive)
print("Negative numbers:", negative)
print("Zeros:", zero)
```

## Output

```text
Positive numbers: 3
Negative numbers: 2
Zeros: 2
```
