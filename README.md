# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program 
### Step 2:
Get the n values from the users
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the output
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: P.KEERTHANA
#RegisterNumber: 23011895
def circulate():
    list1 = eval(input())
    n = int(input())
    result = list1[n:]+list1[:n]
    print("After circulating the values are:" ,result)
```
## Output:
![circulate png](https://github.com/keerthanapillaram/Circulate-the-values-of-N-variables/assets/145743072/f230592e-9e06-4b8f-bf3b-227132634d12)



## Result:
Thus the circulate of two values are successfully executed

