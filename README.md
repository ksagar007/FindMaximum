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
Developed by: K SAGAR KRISHNA
RegisterNumber: 22006940
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python

Program to find the maximum marks using the list method max().
Developed by: K SAGAR KRISHNA
RegisterNumber: 22006940
def max_marks(marks):
    large=max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python

Program to the maximum marks without using builtin functions.
Developed by: K SAGAR KRISHNA
RegisterNumber: 22006940
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot from 2023-01-25 20-47-47](https://user-images.githubusercontent.com/121165786/214606565-cf1722b2-3c07-49a8-82d0-b90a6026229a.png)
![Screenshot from 2023-01-25 20-48-01](https://user-images.githubusercontent.com/121165786/214606619-9ec6381c-9dfb-4fa1-8484-fb91428e40b5.png)
![Screenshot from 2023-01-25 20-48-11](https://user-images.githubusercontent.com/121165786/214606648-569847bc-5ab2-4c49-a82c-991d6891a5f2.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
