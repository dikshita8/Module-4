# Exp.No:18 FILES - FREQUENCY OF CHARACTERS IN A FILE
# AIM
To write a Python program that reads a file and counts the frequency of each character in it.

# ALGORITHM
Begin the program. Define the function create_file() that accepts two arguments: file_path: The path to the file. content: The string content to be written into the file. Open the file specified by file_path in write mode ('w'), and write the provided content into the file. Close the file (this is automatically done when exiting the with block). Define the function character_frequency() that accepts one argument: file_path: The path to the file whose character frequency is to be calculated. Open the file specified by file_path in read mode ('r'), and read its content into the variable content. Initialize an empty dictionary (d1) to store the frequency of each character using defaultdict(int). Loop through each character in the content: For each character ch, increment its corresponding frequency in the dictionary d1. Return the dictionary d1, which contains the frequency of each character in the file. Terminate the program.

# PROGRAM
~~~

a=input()
b=input()
count=0
for i in a:
    if (i==b):
        count+=1 
print("Character "+b+" in the "+a+" is "+str(count)+" times")
~~~
# OUTPUT
<img width="1295" height="313" alt="image" src="https://github.com/user-attachments/assets/79cf9ac6-1962-44fe-a2f7-cc1213fa34b5" />

# RESULT
Thus,the Python program that reads a file and counts the frequency of each character in it is successfully verified.
