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

## i) To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
```

## ii) To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    max_marks=max(marks)
    return max_marks
```

## iii) To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=0
    for i in list1:
        if i>max:
            max=i
    return max   
```
## Output:
## i) To find the maximum of marks using the list method sort.
![image](https://github.com/sanjay5656/FindMaximum/assets/115128955/f25ef660-cc89-49e6-b4d3-7de8cf95013f)

## ii) To find the maximum marks using the list method max().
![image](https://github.com/sanjay5656/FindMaximum/assets/115128955/f879c9a8-9b2e-484e-a725-d47ce6ab9ec0)

## iii) To find the maximum marks without using builtin functions.
![image](https://github.com/sanjay5656/FindMaximum/assets/115128955/902751a7-3338-4ef6-9358-cd95791da919)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
