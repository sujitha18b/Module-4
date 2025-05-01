# Exp.No: 4C
## EXCEPTION HANDLING



### AIM  
To write a python program to Place result="You can't divide with 0" to the right place so that program avoids ZeroDivisionError.

### ALGORITHM

1.Start

2.Take input numerator and denominator

3.Check:

4.If denominator == 0,

5.Set result = "You can't divide with 0"

6.Else,

7.Set result = numerator / denominator

8.Output result

9.End

### PROGRAM

a=int(input())     <br />
b=int(input())      <br />
try:   <br />
    print(a/b)     <br />
except ZeroDivisionError: <br />
    print("You can't divide with 0")
    
### OUTPUT

![Screenshot 2025-05-01 120451](https://github.com/user-attachments/assets/ccee6257-2f82-44aa-9cdd-4c464dc21b0e)

### RESULT
Thus, the given python program is implemented and executed sucessfully.
