# CS101 Spring 2026 — Practice Midterm Reflection

Name: Kathryn Boidock
Date: 03/18/2026

After completing the practice test, please reflect on your experience by
answering the questions below. Replace each `TO-DO` with a thoughtful response
(a few sentences each). Your responses help you consolidate what you learned
and identify areas to review before the real midterm.

---

## 1. Self-Assessment

**Question:** How did you feel about your performance on the practice test?
Which topics felt most comfortable, and which ones felt most difficult?

**Your Answer:**

The for loops felt the easiest to do as I'm quite familiar with them. One question that made me think twice was 'what was considered an integer literal' but after a second of digging I figured it out. 

---

## 2. Tricky Questions

**Question:** Identify one question you got wrong (or were unsure about).
Explain the concept being tested and describe why the correct answer is right.

**Your Answer:**

Question `18. What does the following print?` I was unsure about, only because I still feel a bit new to lambda as a whole, but I figured it out. It uses lambda to combine an if else mathematical statement. Then f(3,7) is called which using the function, is solved. the function itself is inputed as: `f = lambda 3, 7: 3 - 7 if 3 > 7 else 3 + 7` which the result would be using the else statement so, 10.

---

## 3. Loops and Iteration

**Question:** In your own words, explain the difference between `range(a, b, step)`
with a positive step versus a negative step. Give one original example of each.

**Your Answer:**

Using a positive step, a is smaller than b, a being the starting point, and b ebing the ending point. The step is how much the iteration increases from the starting point a until the end point b which is exclusive. THe the negative it is swapped. 
pos - range(2, 11, 2) --> [2, 4, 6, 8, 10]
neg - range(10, 1 , -2) --> [10, 8, 6, 4, 2]

---

## 4. Data Structures

**Question:** Python has lists, tuples, dictionaries, and sets. Describe one key
difference between a list and a tuple, and one key difference between a
dictionary and a set. When would you choose each?

**Your Answer:**

A key difference is that a list is mutable and a tuple is not. A dictionary has key:value pairs and can be repeated, while a set is just a list of unique objects. A list would be great for a school roster to keep track of the students. A tuple would be a good way to keep track of latitude and logitude when it is fixed. A dictionary would be good for names and grades for things.  A set would be useful for removing duplicate answer responses from students.

---

## 5. Functions

**Question:** What is a default parameter in a Python function? Write a short
example function that uses a default parameter, and explain what happens when
the caller omits that argument.

**Your Answer:**

TODO

---

## 6. List Comprehensions

**Question:** List comprehensions can include an optional filter condition.
Rewrite the following traditional loop as a list comprehension:

```python
result = []
for n in range(1, 11):
    if n % 3 == 0:
        result.append(n * 2)
```

**Your Answer:**

TODO

---

## 7. Operator Precedence

**Question:** Python evaluates `**` (exponentiation) right-to-left.
What is the value of `2 ** 2 ** 3`? Show your step-by-step reasoning.

**Your Answer:**

TODO

---

## 8. Classes 

**Question:** What are classes in Python programming? Explain why they are necessary in programming.

**Your Answer:**

TODO

---

(Did you remember to add your name and date at the top of this document?)
(yuh)
