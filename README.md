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
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max


```
## Sample Input and Output
![list method sort sample](https://user-images.githubusercontent.com/121490575/214857375-35c3efed-d718-45a4-89e7-f88c7e405689.png)
![list method max() sample](https://user-images.githubusercontent.com/121490575/214857455-71cf90f8-6362-457c-8290-50ae020dbd38.png)
![builtin function sample](https://user-images.githubusercontent.com/121490575/214857503-48895211-2c98-40d4-8e36-e71cd7602402.png)


## Output:
![list method sort](https://user-images.githubusercontent.com/121490575/214857653-b32da6ed-5a83-4876-ac42-acf75f8eccbd.png)
![list method max](https://user-images.githubusercontent.com/121490575/214857926-bee3bb2e-cef9-49d3-8c02-2df5e0f18d5b.png)
![builtin function](https://user-images.githubusercontent.com/121490575/214858002-5c6f6aca-81cd-475e-a02d-32c558984390.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
