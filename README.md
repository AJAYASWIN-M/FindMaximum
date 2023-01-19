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

def max_marks(list):
    max=list[0]
    for i in list:
        if i>max:
            max = i
    return max
max_marks([88,67,77,93,95,11,67,89,56,89])    


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1=i
    return max1
max_marks([88,67,77,93,95,11,67,89,56,89])    



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot (143)](https://user-images.githubusercontent.com/118679692/213402658-b6ea07f1-2828-49e7-b2a9-df2f536c9f06.png)



![Screenshot (144)](https://user-images.githubusercontent.com/118679692/213402522-25a485aa-6327-494e-9076-f4b959a40c1a.png)



![Screenshot (145)](https://user-images.githubusercontent.com/118679692/213402405-ccf5478f-821e-4e58-ad44-b72269940ed6.png)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
