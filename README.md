# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the value from the user for the number of rotation.

### Step 2: 
Using the slicing concept rotate the list.

### Step 3: 
Print the result(Rotated list).

### Step 4: 
End of program.


## Program:
~~~
def circulate():
    n=int(input())
    l=[10,20,30,40,50,60]
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
~~~

## Output:
![GitHub Logo](CIRCULATE.png)

## Result:
Thus the values are circulated succefully.
