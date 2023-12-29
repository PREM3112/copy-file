# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required the from which we need to copy the text.
### Step 2: 
Using keyword "with" to open the required file. 
### Step 3: 
Again using the with keyword to open the empty file.
### Step 4:  
The empty file is open by using 'W' which is used to write only.
### Step 5: 
The for function is used to take each line from the main file
### Step 6: 
Write() is used to write the lines of main file to the empty file or to the directed file.
## PROGRAM:
```
with open("text.txt","r") as f1:
    data=f1.read()
with open("data.txt","w") as f2:
    f2.write(data)
```
### TEXT FILE:
```
with open("text.txt",'w')as fp:
  fp.write("Hello World")
  fp.write("\nWelcome to Python")
  fp.write("\nHave a Good Day")
  ```
### EMPTY FILE:
```
with open("data.txt","w") as fd:
 fd.write("")
 ```
### COPY FILE:
```
with open("data.txt","r") as f2:
  data1=f2.read()
  print(data)
```
### OUTPUT:
![1](https://github.com/PREM3112/copy-file/assets/145449383/78bf996b-4dae-4c93-b056-93b7d490b753)
![2](https://github.com/PREM3112/copy-file/assets/145449383/7dd87c17-06d3-4540-8aa6-03147d62fef8)
![3](https://github.com/PREM3112/copy-file/assets/145449383/74d949bd-aef3-4be4-a8b0-7b7bc03243d6)
![4](https://github.com/PREM3112/copy-file/assets/145449383/f8b29c41-207d-43a2-ba99-f8d4c200174e)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
