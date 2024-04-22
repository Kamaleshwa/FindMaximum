# Find the maximum of a list of numbers

## Aim:

To write a program to find the maximum of a list of numbers.

## Equipment’s required:

1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

1. Get the list of marks as input
2. Use the sort() function or max() function or use the for loop to find the maximum mark.
3. Return the maximum value

## Program:

i) # To find the maximum of marks using the list method sort.

```Python
# Program to mark the maximum of marks using the list method sort.
# Developed by: KAMALESHWAR KV
# Register No:212223230063
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii) # To find the maximum marks using the list method max().

```Python
# Program to find the maximum marks using the list method max().
# Developed by: KAMALESHWARV KV
# Register No: 212223230063
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.

```Python
# Program to find the maximum marks without using builtin functions.
# Developed by: KAMALESHWAR KV
# Register No: 212223230063
def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark


```

## Output:

i) # To find the maximum of marks using the list method sort.
![image](https://github.com/Kamaleshwa/FindMaximum/assets/144980199/bfa846c0-21ab-40f4-bf9d-cd50af2b40af)

ii) # To find the maximum marks using the list method max().
![image](https://github.com/Kamaleshwa/FindMaximum/assets/144980199/08702fd9-ec76-4eb8-9c61-be5b1ec75b50)


iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/Kamaleshwa/FindMaximum/assets/144980199/61059136-cf72-4692-9b9f-580b0e4430b2)



## Result:

Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
