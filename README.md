# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np
### Step 2: 
Enter the input values
### Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments
### Step 4:  
Run the program
### Step 5: 
 Input the values
### Step 6: 
 End the program
## PROGRAM:
```
## Developed by : DEVADHAARINI.D
## Register no.: 212223230040
num=0
with open("rename.txt","r")as f1:
    for i in f1:
        word=i.split()
        num+=len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:
![Screenshot 2024-05-15 211044](https://github.com/Devadhaarini/Word-Count/assets/145796552/3390eeb8-b63d-4f08-8b26-10d29a24efbb)
## RESULT:
Thus the program is written to find the word count from a text.
