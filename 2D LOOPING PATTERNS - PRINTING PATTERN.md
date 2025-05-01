# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To write a Python program to print a triangular star pattern using loops.

---

### ALGORITHM

1. Begin the program.  
2. Read the integer `n` from the user using `input()`. This will determine the number of rows in the pattern.  
3. Initialize a variable `i = 0`. This will help adjust the spacing before the stars.  
4. Loop through rows from `0` to `n - 1`:  
   - For each row, calculate the number of spaces to print using the formula: `((n - rows - 1) * 2) + i`.  
   - Print the calculated number of spaces using `print(" ", end="")`.  
   - Increment `i` by 1 after each row.  
   - Print stars using a nested loop: the number of stars in each row is `rows + 1`, printed using `print("*", end="  ")`.  
   - Print a newline after each row using `print("")` to move to the next line.  
5. Terminate the program.

---

### PROGRAM
```
#Reg.No: 212223060288
#Name: Tharun Kumaran G

rows = int(input("Enter the number of rows: "))

for i in range(1, rows + 1):
    print('/' * i)


```

### OUTPUT

![image](https://github.com/user-attachments/assets/8d9d3782-0ffb-49d7-a5d2-8260941d4902)

### RESULT

Thus, the python program to print a triangular star pattern using loops has been executed and verified successfully.
