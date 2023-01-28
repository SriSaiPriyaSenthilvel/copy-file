# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Open the first file in read mode.

### Step 2: Open the second file in append mode.
 
### Step 3: Every word in the first file is copied to second file using write().

### Step 4: Close the first file.

### Step 5: Close the second file.

### Step 6: End the program.

## PROGRAM:
```
Python program for copying a file.
Program developed by: Sri Sai Priya.S
Reference number: 22006141
f1=open("f11.txt","r")
f2=opem("f12.txt","a")
for line in f1:
    f2.write(line)
    f1.close()
    f2.close()
```

### OUTPUT:
 
 ![output](/Screenshot%20from%202023-01-28%2012-25-13.png)

![output](/Screenshot%20from%202023-01-28%2012-24-30.png)

recent:///ac2fe7d73f32097acd32110f63d4cb3b
 


## RESULT:
Thus the program is written to copy the contents from one file to another files.
