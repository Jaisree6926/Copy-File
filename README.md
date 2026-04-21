# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
 Write some lines in that file.
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output
## PROGRAM:
```python
#Program for copying the contents from one file to another file.

with open("file1.txt","r") as f1:
    with open("copy.txt","w") as f2:
        line=f1.read()
        f2.write(line)

```
### OUTPUT:

<img width="943" height="163" alt="image" src="https://github.com/user-attachments/assets/9a7511ac-5b5b-4906-8778-b63280f94a40" />

## RESULT:
Thus the program is written to copy the contents from one file to another file.
