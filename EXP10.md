# Ex.No: 10  Pytest program for Fibonacci Series

### NAME : Varsha G                                                                           
### REGISTER NUMBER : 212222230166

### AIM: 
To write a python program for Fibonacci Series and generate test cases using Pytest. 

### Algorithm:

1. Write the python program for Fibonacci Series. 
2. Make sure that function name should be “def test_*():” and the line to be tested 
should have assert keyword at the beginning. 
3. Write some test cases for to be tested and save it as “test_fib.py”. 
4. Open command prompt and change the directory to where pytest and program is 
saved and type “pytest test_fib.py” and run it. 
5. Stop the program.

### Program:

```
def fibR(n): 
    if n == 1 or n == 2: 
        return 1 
    return fibR(n - 1) + fibR(n - 2) 

def test_fib_1_equals_1(): 
    assert fibR(1) == 1 

def test_fib_2_equals_1(): 
    assert fibR(2) == 1 

def test_fib_6_equals_8(): 
    assert fibR(6) == 7

```

### Output:
![WhatsApp Image 2025-11-05 at 20 08 02_d2ac4447](https://github.com/user-attachments/assets/ff43b9b2-9960-49c2-9e3d-66084246a00c)


### Result:
Thus, the python program for Fibonacci Series is tested using pytest and executed and output is verified successfully.
