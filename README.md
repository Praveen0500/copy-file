# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file from which we need to copy the text.

### Step 2:
Using keyword "with" to open the required file.

### Step 3:
Again using the with keyword to open the empty file.

### Step 4:
The empty file is open by using 'w' which is used to write only.

### Step 5:
The for function is used to take each line from the main file.

### Step 6:
write() is used to write the lines of main file to the empty file or to the directed file.

## PROGRAM:
```
'''
Developed by:praveen  s
Register Number:22009060
'''
with open('text.txt','r') as firstfile:
    with open('text2.txt','a') as secondfile:
        for line in firstfile:
            secondfile.write(line)
```

### OUTPUT:

![5c data1](https://user-images.githubusercontent.com/120218611/214780576-c2387549-2374-48e2-b63b-6c3f472fb7fc.png)

![5c output](https://user-images.githubusercontent.com/120218611/214780595-0b8d62ee-990d-427d-a2b9-7406145349f5.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
