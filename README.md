# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open a text file as firstfile using with open command
### Step 2: 
Open another text file as secondfile using with open command 
### Step 3: 
Using for loop , reading the content inside firstfile.
### Step 4:  
Copying first file in second file
### Step 5: 
Run the Program. The First file will be copyed in second file
### Step 6: 
End the program
## PROGRAM:
#Devolped By: PRAVEEN KUMAR S
#Ref no: 22004035
```
with open('sample.txt','r') as file1:
    with open ('san1.txt','a') as file2:
        for line in file1:
            file2.write(line)
```
### OUTPUT:
![copy file](https://user-images.githubusercontent.com/119559827/214614499-749fa4e0-ce04-40d6-99a0-53a4d07a0a95.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
