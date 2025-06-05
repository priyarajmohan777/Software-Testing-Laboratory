# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 06/03/2025                                                                      
### REGISTER NUMBER : 212222040124

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

### i.)do…while: 

```
def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
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
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch() 

```

### iv.) if else

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
        print(“Enter a valid number.”) 

```

### v.) for

```
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 
```




### Output:

#### Do While
![STL 1](https://github.com/user-attachments/assets/82437ebd-6f04-4ae8-bd11-b5ec1176a359)
#### While Do
![STL 2](https://github.com/user-attachments/assets/98d49407-0396-42ba-ad3d-4357ada74442)
#### Switch
![STL 3](https://github.com/user-attachments/assets/80d8f97e-be8f-46b5-8601-5918e0fb74ca)
#### If Else
![STL 4](https://github.com/user-attachments/assets/9a1a0efa-1321-499e-a473-effdbf912dc0)
#### For
![STL 5](https://github.com/user-attachments/assets/c7a3f053-76cd-47a7-bd06-1aa6eda3d72c)


### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
