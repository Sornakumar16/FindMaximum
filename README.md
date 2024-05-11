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
#DEVELOPED BY: SORNA KUMAR S
#REGISTER NUMBER: 212223230210
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
#DEVELOPED BY: SORNA KUMAR S
#REGISTER NO: 212223230210
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
#DEVELOPED BY: SORNA KUMAR S
#REGISTER NO: 212223230210
def max_marks(list1):
    max_num=list1[0]
    for i in list1:
        if i>max_num:
            max_num=i
    return max_num
```



## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/Sornakumar16/FindMaximum/assets/138849327/b391c238-8330-4247-88d9-c4b6c059bbd0)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/Sornakumar16/FindMaximum/assets/138849327/9ae20b29-d0f4-432d-bff0-6e48a236f326)

iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/Sornakumar16/FindMaximum/assets/138849327/9cf087a7-f832-4142-883c-d0f53f12c330)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
