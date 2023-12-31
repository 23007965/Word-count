# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a variable num and set it to 0. This variable will store the total word count.
### Step 2: 
Use the open() function to open the file named "sample.txt" in read mode ("r").Store the file object in a variable, such as f1.
### Step 3: 
Iterate through each line in the file using a for loop.Split the line into a list of words using the split() method.Count the number of words in the list using the len() function.
### Step 4:  
Add the word count to the num variable.
### Step 5: 
After processing all lines, print the total word count using print().
### Step 6: 
The with statement automatically closes the file when the block ends.


## PROGRAM:
#Progream to find the Word Count
#Developed by: P PARTHIBAN
#Register Number: 23007965

num=0
with open("sample.txt","r") as f1:
    for i in f1:
        word=i.split()
        num+=len(word)
    print("The number of words are in the file is",num)

### OUTPUT:
![Screenshot 2023-12-31 221053](https://github.com/23007965/Word-count/assets/138971238/6789dce9-df00-423e-8b47-7bac8a58d2a8)

![Screenshot 2023-12-31 221218](https://github.com/23007965/Word-count/assets/138971238/bd2aab84-0f09-4bda-af6a-8624e6db5b0f)


## RESULT:
Thus the program is written to find the word count from a text.
