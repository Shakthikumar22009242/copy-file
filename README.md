# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
By using open function open the file from where we want to copy from and access it in read mode.
### Step 2: 
Read the file and store in a variable.
### Step 3: 
Then create a new file where we want to paste the content using write access mode.
### Step 4:  
With write function copy the read file that has been stored in the variable.
### Step 5: 
In the new file the content from the original file gets copied.
### Step 6: 
End the program.
## PROGRAM:
Developed by:Shakthi Kumar
RegisterNumber: 22009242
```python
with open("f45.txt","r") as fp:
    x = fp.read()
with open("f44.txt","w") as fp1:
    fp1.write(x)
```
### OUTPUT:
![](copy1.png)
![](copy2.png)
## RESULT:
Thus the program is written to copy the contents from one file to another file.