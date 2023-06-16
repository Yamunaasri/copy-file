# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it


### Step 2: 
Open the text1.txt file in read mode


### Step 3: 
Create a copy.txt file using write mode


### Step 4:  
Copy the content of text1.txt file to copy.txt using write function


## PROGRAM:

''' 
Program for copying the contents from one file to another file
Developed by: T S Yamunaasri
RegisterNumber: 21222240117
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
### OUTPUT:

![image](https://github.com/Yamunaasri/copy-file/assets/115707860/e2be146b-78bd-4556-87fe-cd0b6120b6f5)
![image](https://github.com/Yamunaasri/copy-file/assets/115707860/c35fcf2a-2177-4af1-9af7-e714ff7d1eae)
![image](https://github.com/Yamunaasri/copy-file/assets/115707860/c92f6762-7465-4d2d-b3a0-a245ab8f31ce)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
