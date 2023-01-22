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
Developed by: Gumma Dileep Kumar
RegisterNumber: 22007129
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: Gumma Dileep Kumar
RegisterNumber: 22007129
'''
def max_marks(marks):
    large=max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: Gumma Dileep Kumar
RegisterNumber: 22007129
'''
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>=max1:
            max1=i
    return max1    



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![maximum_sort_output](https://user-images.githubusercontent.com/118707761/213904223-82acc46f-c32e-4694-9b51-ab215a1ac396.png)
![maximum_2_output](https://user-images.githubusercontent.com/118707761/213904226-c6a3f36d-e987-4316-8d4e-ceb974049fc8.png)
![maximum_3_output](https://user-images.githubusercontent.com/118707761/213904235-4e52b4b1-c7aa-4eec-9a57-a002190f6ec0.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
