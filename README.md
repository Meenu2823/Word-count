# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in text mode.

### Step 2:
Read the text using read() function.

### Step 3:
Split the text using space separator.We assume that words in a sentance are separted by a space character.

### Step 4:
The length of the split list should equal the numbers of words in the test file.

### Step 5:
Store the length of the split list in a variable and print the result.

### Step 6:
End the program.
 

## PROGRAM:
~~~python
#Program to count the number of words in a textfile
#Developed by :Meenu.S
#Register umber : 23003303
from google.colab import drive
drive.mount('/content/drive')


f=open(r"/content/drive/My Drive/example_file.txt","r")
a=f.read()
print(a)
b=a.split()
count=len(b)
print("The number of words in the file is:",count)

~~~

### OUTPUT:
![count](<python 5a.png>)


## RESULT:
Thus the program is written to find the word count from a text.
