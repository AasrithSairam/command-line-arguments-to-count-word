# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Import the sys module

### Step 2: Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
 
### Step 3: Read the file using read() method.

### Step 4: Use split() method to split the file content into words.

### Step 5: Use len() to find the total words.

### Step 6: Run the program to determine the number of words in the file created.

## PROGRAM:
```
Python program for getting the word count from the contents of a file using command line arguments.
Developed by: ponguru aasrith sairam
RegisterNumber: 23007809

import sys
count = 0
with open (sys.argv[1],'r') as f1:
    for line in f1:
        word = line.split()
        count += len (word)
print("word count in file = ",count)
```

### OUTPUT:
![image](https://github.com/AasrithSairam/command-line-arguments-to-count-word/assets/139331438/b3f5c929-4dcf-4723-bf6b-7808da7db0c4)
![image](https://github.com/AasrithSairam/command-line-arguments-to-count-word/assets/139331438/d261e11e-e107-4dde-b93e-8510d2783864)
![image](https://github.com/AasrithSairam/command-line-arguments-to-count-word/assets/139331438/e8bf87b6-1fcc-49ca-87e7-2d3f775f0662)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
