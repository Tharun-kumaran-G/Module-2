# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM

```
#Reg_no: 212223060288
#Name: Tharun Kumaran G

compare = lambda a, b: "greater than" if a > b else ("equal to" if a == b else "less than")

a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

print(f"{num1} is {compare(num1, num2)} {num2}")
```

### OUTPUT

![image](https://github.com/user-attachments/assets/68bfca6c-e0e8-416a-99ac-6e7bc78468d4)


### RESULT

Thus, the python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function has been executed and verified successfully.
