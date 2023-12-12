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
def max_marks(marks):
    marks.sort()
    highest=marks[-1]
    return highest



```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    marks1=max(marks)
    return marks1


```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
            


``````

## Output:
![image](https://github.com/Vickyy-0/FindMaximum/assets/110780412/4e117486-30a8-4241-a994-2dd88693919d)
![image](https://github.com/Vickyy-0/FindMaximum/assets/110780412/681feee5-be7e-4656-9eb0-e65d84097d85)
![image](https://github.com/Vickyy-0/FindMaximum/assets/110780412/e675e87f-2ed0-4efa-aef9-4b3ed4790690)









## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
