# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Create the file.
### Step 2:

Write some lines in that file.
### Step 3:

Create python file.
### Step 4:

Write a code to copy the content of the file to a new file.
### Step 5:

Run the program.
### Step 6:

Display the output.
## PROGRAM:
```
'''
Developed by: SARAVANAN G
RegisterNumber: 23005445
'''
def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
```
### OUTPUT:


![293370763-c11d0b1a-4f27-4db3-bc15-dea8f44588e3](https://github.com/Saravanan2512/copy-file/assets/144979117/366c526c-5d06-4c0e-88a7-87a31b1bf325)
![293370697-4b52e56b-2b04-4afb-9b47-19703c2d9573](https://github.com/Saravanan2512/copy-file/assets/144979117/02465e33-fa37-4a33-bc0f-c9e1f028adc6)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
