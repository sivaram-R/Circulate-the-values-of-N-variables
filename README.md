# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
import def circulate
### Step 2: 
prepare the lists from each linear equation and assign in np.array()
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
add coding to input value 
### Step 6: 
print the coding to get answer 
## Program:
```
#Program to circulate N values.
#Developed by: sivaram R
#RegisterNumber:22008680
def circulate():
 l=eval(input())
 n=int(input())
 l=l[n:]+l[:n]
 print("After circulating the values are:",l)
```
## Output:

![circulate](https://user-images.githubusercontent.com/121165794/209470345-be527637-1866-4633-94a7-9db549f51f22.png)
![circulate2](https://user-images.githubusercontent.com/121165794/209470348-49e3e4e9-2288-4b93-9c9d-869173051683.png)

## Result:
 The program executed successfully
