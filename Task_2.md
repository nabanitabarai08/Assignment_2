---

# Sum of Numbers from 1 to 50 

## Description

This Python program calculates the **sum of all natural numbers from 1 to 50** using a `for` loop.
It adds each number step-by-step and displays the final result.

---

## How It Works

* A variable `sum` is initialized to `0`.
* A `for` loop runs from `1` to `50`.
* Each number in the loop is added to `sum`.
* After the loop ends, the total sum is printed.

---

## Code Explanation

```python
sum = 0
```

* Initializes a variable to store the total sum.

```python
for i in range(1, 51):
```

* Loops from `1` to `50` (`51` is excluded).

```python
sum = sum + i
```

* Adds the current value of `i` to `sum`.

```python
print("The sum of numbers from 1 to 50 is : ", sum)
```

* Displays the final sum.

---

##  Sample Output

```
The sum of numbers from 1 to 50 is :  1275
```
