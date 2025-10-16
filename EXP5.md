### Ex.No: 5 check the given number is present in array or not and inspect for failures.
### NAME: VARSHA G
### REG NO: 212222230166
### DATE : 16/10/2025

### AIM: 
Write a python program to check the given number is present in array or not and inspect for failures

### Algorithm:

1.  Start the program.
2.	Initialize an array with some elements.
3.	Get an input from the user for the number to be searched.
4.	Convert the user input to an integer.
5.	Set low = 0 and high = length of array - 1.
6.	Repeat the following steps while low <= high:
    a. Calculate mid = (low + high) // 2.
  	b. If arr[mid] == number, print that the element is found at index mid and stop.
  	c. If arr[mid] < number, set low = mid + 1.
  	d. Else, set high = mid - 1.
7.	If the loop ends and the element is not found, print that the element is not present in the array.
8.	If the user enters invalid input (not a number), display an error message.
9.	Stop

### Program:
```
def binary_search(arr, x):
    low = 0
    high = len(arr) - 1
    mid = 0

    while low <= high:
        mid = (high + low) // 2

     
        if arr[mid] < x:
            low = mid + 1
        elif arr[mid] > x:
            high = mid - 1
        else:
            return mid 
    return -1  

arr = [2, 3, 4, 10, 40]


x = input("Enter the element to be searched: ")

try:
    x = int(x)  
    result = binary_search(arr, x) 

    if result != -1:
        print("Element is present at index", str(result))
    else:
        print("Element is not present in array")

except ValueError:
    print("Enter a valid input!")  

```

### Output:



### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.
