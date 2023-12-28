# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC Anaconda - Python 3.7
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
Display the output.
## PROGRAM:
```
'''
#Developed By:Kolluru Pujitha
#Register No: 23002983
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
![image](https://github.com/KolluruPujitha/copy-file/assets/150231340/566e9e11-a405-442b-bc0f-001dff307835)
![image](https://github.com/KolluruPujitha/copy-file/assets/150231340/e04932f4-6b00-4566-a2a7-9c1cad94a403)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
