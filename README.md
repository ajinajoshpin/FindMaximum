# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

step 1:

Get the list of marks as input

step 2:

Use the sort() function or max() function or use the for loop to find the maximum mark.

step 3:

Return the maximum value

## Program:

i	 To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: ajina joshpin
RegisterNumber: 23013547
'''
def max_marks(marks_list):
   marks_list.sort()
   max_mark=marks_list[-1]
   return max_mark


```

ii	 To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:ajina joshpin
RegisterNumber: 23013547
'''
def max_marks(marks_list):
    marks_list.sort()
    max_mark=marks_list[-1]
    return max_mark
  


```

iii To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: ajina joshpin
RegisterNumber: 23013547
'''
def max_marks(list1):
    max=0
    for i in list1:
        if i>max:
            max=i
    return max


```
## To find the maximum of marks using the list method sort.
![image](https://github.com/ajinajoshpin/FindMaximum/assets/148514578/2e7143f4-a65d-4cdc-9b80-9847b4701166)
## To find the maximum marks using the list method max().
![image](https://github.com/ajinajoshpin/FindMaximum/assets/148514578/63df2031-0abc-4e88-b6d9-73cce7ae416f)
## To find the maximum marks without using builtin functions.
![image](https://github.com/ajinajoshpin/FindMaximum/assets/148514578/4ec9d16f-a1d3-4023-9a5c-67b6fc2dc3b8)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
