# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2: 
The filename must be passed as the first argument after the name of the script itself.
Open the file has sys.argv[1].
### Step 3: 
Read the file using read().
### Step 4:  
Use split() to split the file content  into words .
### Step 5: 
Use len() to find the total words .


## PROGRAM:
```
import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```

### OUTPUT:
![Output](./terminalop.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
