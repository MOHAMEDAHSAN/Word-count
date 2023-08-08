# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import drive from google.colab and mount the drive to access the text file
### Step 2: 
Create a new file object and create a text file
### Step 3: 
Write into the text file and close it
### Step 4:  
Open the created file in read mode
### Step 5: 
Using len() function find the word count and display it
### Step 6: 
Close the file object
## PROGRAM:
~~~Python
# PYTHON WORD COUNT - .txt file
# Developed by : S MOHAMED AHSAN
# Register No : 23001044

from google.colab import drive
drive.mount('/content/drive')
f=open('/content/drive/My Drive/EXP5.txt','w')
f.write('''From the outside, it might just seem like any other anime show centering around kids with cool skills.
But if you’d like to know what this show is really about and why it’s so popular.''')
f.close()
f=open('/content/drive/My Drive/EXP5.txt','r')
r1=f.read().split()
print('Count :',len(r1))
f.close()
~~~
## OUTPUT:
![PIC1](/wd.png)
#### .txt File : 
![PIC2](/txt.png)


## RESULT:
Thus the program is written to find the word count from a text.
