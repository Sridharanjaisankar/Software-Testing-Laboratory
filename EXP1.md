# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 13.8.2024                                                                           
### REGISTER NUMBER : 212222040158

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
### 1.Do...While
```
def display(): 
    start=input("Enter a positive value for START: ") 
    end=input("Enter a positive value for END: ") 
    if start.isnumeric() and end.isnumeric(): 
        while True: 
            start=int(start) 
            end=int(end) 
            print(start,end='') 
            if start<end: 
                start+=1 
            else: 
                break 
    else: 
        print("Enter a valid positive number.") 
display()

```
### 2.While...Do
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
### 3.Switch
```
def switch(): 
    switcher={ 
    0:"even", 
        1:"odd" 
    } 
    n=input('Enter a value for N: ')
    try: 
        n=int(n) 
        print(switcher[n%2]) 
    except ValueError: 
        print("Enter a valid number.")
switch()

```
### 4.If...Else
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
### 5.For
```
def iterate(): 
    string=input("Enter a string: ")
    for i in string: 
        print(ord(i),end=" ")
iterate()

```



### Output:
### 1.Do...While
![1ao](https://github.com/user-attachments/assets/b556d57c-e093-46f2-b6a8-4640115c0187)

### 2.While...Do
![1bo](https://github.com/user-attachments/assets/167d0485-8b0c-447b-aa04-18a04bce460c)

### 3.Switch
![1co](https://github.com/user-attachments/assets/452985ec-1aba-4d8d-bebb-e2cf5a6da05b)

### 4.If...Else
![1do](https://github.com/user-attachments/assets/fe7745fb-192d-4bf8-b076-a15f9d0de8ef)

### 5.For
![1eo](https://github.com/user-attachments/assets/a7957765-2ecf-4194-b2bd-e34ce0cc91f2)








### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


