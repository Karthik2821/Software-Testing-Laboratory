# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
   
### Program:
### i.)do…while: 
```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        
        if start > 0 and end > 0:  
            while start <= end:    
                print(start, end=' ')
                start += 1
    else:
        print("Enter a valid positive number.")

display()
```
### ii.) while…do 
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

### iii.) switch
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }
    
    n = input('Enter a value for N: ')
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
```

### iv.) if else:
```
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    try:
        a = int(a)
        b = int(b)
        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    except
```
### v.) for:
```
def iterate():
    string = input("Enter a string: ")
    for i in string:
        print(ord(i), end=" ")

iterate()
```

### Output:
### i.)do…while: 

![Screenshot (133)](https://github.com/user-attachments/assets/5b330fa4-1572-4874-9814-228d7f187f03)

### ii.) while…do:

![Screenshot (136)](https://github.com/user-attachments/assets/d984ab63-9226-4c05-a2b3-e5004ee96d0f)

### iii.) switch

![image](https://github.com/user-attachments/assets/945bf634-e0fe-4aee-97a8-f0b77ba6e711)

### iv.) if else:

![image](https://github.com/user-attachments/assets/eec9813e-707a-4146-bb45-256ff11948e1)

### v.) for:

![image](https://github.com/user-attachments/assets/665c6818-5328-4830-9f17-6be200ffc47c)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
