# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### NAME: Varsha G                                                                         
### REGISTER NUMBER : 212222230166

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

## Do while
```
def display():
    start=input("Enter a positive value for START: ")
    end=input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=' ')
            if start<end:
                start+=1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()
```

## while do

```
start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
    start=int(start)
    end=int(end)
    while start<end:
        print(start)
        start+=1
else:
    print("Enter a valid positive number.")
```

## Switch

```
def switch():
    switcher={0:"even",1:"odd"}
    n=input('Enter a value for N: ')
    try:
        n=int(n)
        print(switcher[n%2])
    except ValueError:
        print("Enter a valid number.")
switch()

```

## If else

```
def compare():
    a=input("Enter a value for A: ")
    b=input("Enter a value for B: ")
    try:
        a=int(a)
        b=int(b)
        if a>b:
            print("A is greater than")
        elif a<b:
            print("B is greater than")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")

compare()
```

## for

```
def iterate():
    string=input("Enter a string: ") 
    for i in string:
        print(ord(i),end=" ")
iterate()
```

### Output:

## Do while
![630ab813-1c80-4c7a-8525-7dc123143ca9](https://github.com/user-attachments/assets/5723abfc-5680-441b-8f7b-a9eefa765fe7)


## While do
![36c06941-5427-4508-bc0a-8ca62eb3ad42](https://github.com/user-attachments/assets/7df28095-5e3f-4e73-ae1b-009920813540)


## Switch
![001cb3e8-7e11-410e-a337-9fa9d570b4b1](https://github.com/user-attachments/assets/aaa97053-3833-4ff1-b173-c97c114a0990)


## If else
  ![stl1d](https://github.com/user-attachments/assets/23e82684-68e4-4a34-b7d7-28fd14bde424)


## for
![stl1e](https://github.com/user-attachments/assets/059fee5a-54e8-4533-b4aa-12bd4a4ae912)



### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
