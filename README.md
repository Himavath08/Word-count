# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## STEP 1: Prompt the user to enter the name of the file they want to analyze for word count
## Step 2: Initialize a variable to store the total word count and open the specified file in read mode.
## Step 3: Iterate through each line in the file using a loop and split the line into words using the split() method.
## Step 4: Add the number of words in each line to the word count variable using the len() function.
## Step 5: Repeat the process for all lines in the file until the end of the file is reached.
## Step 6: Print the final word count of the text file after the loop ends, thereby completing the Python program for word counting.

## PROGRAM:
```
# Program to count the no. of words in a file.
# Developed by: M HIMAVATH
# Reg.no: 23010121
fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
  print("Number of words:",num_words)
```
### OUTPUT:
![WhatsApp Image 2023-12-25 at 08 26 23_36b56d39](https://github.com/Himavath08/Word-count/assets/139110631/d7bbd2a9-ead5-413f-89f4-48401b337206)



## RESULT:
Thus the program is written to find the word count from a text.
