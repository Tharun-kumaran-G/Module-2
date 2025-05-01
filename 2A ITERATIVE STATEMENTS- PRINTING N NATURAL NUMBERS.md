# Exp. No: 2a  
## ITERATIVE STATEMENTS – PRINTING N NATURAL NUMBERS

###  Aim
To create a Python program for printing `n` natural numbers using a `for` loop.

---

###  Algorithm

1. Begin the program.
2. Use `input()` to read the value of `n` (the upper limit) from the user.
3. Convert the input to an integer.
4. Display the message **"Natural Numbers are :"**.
5. Use a `for` loop to iterate from 1 to `n` (inclusive).
6. In each iteration, print the current value of `i`.
7. Terminate the program.

---

### 🧾 Program

```python
#Reg.NO - 212223060288
#Name - Tharun Kumaran G

n = int(input())
if n <= 0:
    print()
else:
    print(f"First {n} natural numbers are:")
    for i in range(1, n + 1):
        print(i)

```
### OUTPUT

![image](https://github.com/user-attachments/assets/82a31238-8341-4ae7-a6ed-3c7fdfafd4ea)

### RESULT

Thus, the python program to print n natural numbers using for loop has been executed and verified succesfully.


