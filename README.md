# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location form the user

### Step 2: 
 Give a new name to create the copy of the content

### Step 3: 
Read the file and close the file

### Step 4:  
Now write the content in the new file 

### Step 5: 
when done print "File copied successfully

### Step 6: 
End the program

## PROGRAM:


#Developed by: Priyadharshini Raja
#Register number: 23013809

def copy(fname,newfile):
    with open(fname,'r')as fp:
        with open(newfile,'w')as fp1:
          data=fp.read()
          fp1.write(data)
fname=input("Enter an existing file:")
newfile=input("Enter a name for new file:")
copy(fname,newfile)

 

### OUTPUT:
![output](<copy file ss.png>)


## RESULT:
Thus the program is written to copy the contents from one file to another file.