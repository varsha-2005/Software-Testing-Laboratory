# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 28/08/2025
### NAME: Varsha G                                                                        
### REGISTER NUMBER : 212222040044

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

## while 

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
![7fbc0d41-b629-426c-a3d5-ad933f406d2b](https://github.com/user-attachments/assets/1f464d36-7ae7-4e79-ba0a-4cd6fc5326d1)


## While 
![2a39f31b-0d41-4d43-bb71-5973565e68a6](https://github.com/user-attachments/assets/95db6053-0918-40d7-9dd9-abf1ad0bf470)


## Switch
![09b953e8-2d73-4275-b761-f1dacd8d531a](https://github.com/user-attachments/assets/67359367-b8db-41e9-b69b-718e449234b5)


## If else
![754511ed-3100-4b7a-a628-d61fd0563705](https://github.com/user-attachments/assets/25b0c1d3-0824-450d-9efd-4e528db6b3d6)

## for
![ac6bccca-ccd3-4faa-8d99-b1114f836b0d](https://github.com/user-attachments/assets/d862a942-3c9c-4e6e-b4f2-108d25eb87a3)



### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
