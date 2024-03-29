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
```
Program to find maximum of marks using the list method sort
Devoloped by:KATHIRESAN K
reg. no:2122310021
```
```
def max_marks(array):
    array.sort()
    return array[-1]
```
ii)	# To find the maximum marks using the list method max().
```
Program to find maximum of marks using the list method max()
Devoloped by:KATHIRESAN K
reg. no:2122310021
```
```
def max_marks(array):
    return max(array)
```
iii) # To find the maximum marks without using builtin functions.

```
Program to find maximum of marks without using builtin function
Devoloped by:KATHIRESAN K
reg. no:2122310021
```
```
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1
```
## Output:
![image](https://github.com/Kathiresan-23013376/FindMaximum/assets/150008375/b6898e12-ef0c-4c5d-826d-d14e51ed9614)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
