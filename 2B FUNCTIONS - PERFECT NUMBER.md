# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```
#Reg.No: 212223060288
#Name: Tharun Kumaran G

def perfect(num):
    sum = 0
    for i in range(1, num):
        if num % i == 0:
            sum += i
    return sum == num
n = int(input())
if perfect(n):
    print(f"{n} is a perfect Number.")
else:
    print(f"{n} is not a perfect Number.")

```
### OUTPUT

![image](https://github.com/user-attachments/assets/8774ddb8-769b-40aa-b9d3-1b4eb52aeab2)

### RESULT

Thus, the python program to check if a given number is a perfect number using the concept of functions has been executed and verified successfully.
