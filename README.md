# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:

## Step 1:
Import numpy as np

## Step 2:
Enter the input values

## Step 3:
Write python program for getting the word count from the contents of a file using command line arguments

## Step 4:
Run the program

## Step 5:
Input the values

## Step 6:
End the program

## PROGRAM:
```
#program to find the number of words in a text file
#Developed by : MANIKUMAR DK
#Register number : 212223230121

num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)                        
```
### OUTPUT:

![image](https://github.com/MANIKUMARDK/Word-Count/assets/147215581/890d8c77-2e8d-4338-8a91-e1f52deeb3ad)

![image](https://github.com/SanjaiOfficial/Word-Count/assets/151763180/d6b9998e-698a-471b-bba1-5eaf182e5ef1)



## RESULT:
Thus the program is written to find the word count from a text.
