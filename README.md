# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
Program to mark the maximum of marks using the list method sort
Developed by: C Saravanan
RegisterNumber: 22008175000.
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
    #Write your code here
    



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: C Saravanan
RegisterNumber: 22008175
'''
def max_marks(marks):
    large = max(marks)
    return large
    # write your code here
    
    
    



```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: C Saravanan
RegisterNumber: 22008175
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        
    



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Exp-1a CR Swapping of two variables_ Attempt review - Google Chrome 15-06-2023 09_34_46 (2)](https://github.com/saravanan2607/FindMaximum/assets/121395849/c94df31d-da90-4cc6-b59c-a2a05708cfad)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
