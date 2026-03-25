# Exp.No:16 DICTIONARY - SIZE OF DICTIONARY
# AIM
To write a Python program to print the size of a dictionary using getsizeof() from the sys module.

# ALGORITHM
Begin the program. Import the sys module to use the getsizeof() function. Define the dictionaries with key-value pairs (dic1, dic2, dic3). Use sys.getsizeof() to calculate the memory size of each dictionary. Print the size of each dictionary in bytes. Terminate the program.

# PROGRAM
~~~


import sys
dic1 = {"A": 1, "B": 2, "C": 3} 

dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}

dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}

size_dic1=sys. getsizeof(dic1)
size_dic2=sys. getsizeof(dic2)
size_dic3=sys. getsizeof(dic3)

print("Size of dic1: "+str(size_dic1) +"bytes")
print("Size of dic2: "+str(size_dic2) +"bytes")
print("Size of dic3: "+str(size_dic3) +"bytes")
~~~
# OUTPUT
<img width="934" height="242" alt="image" src="https://github.com/user-attachments/assets/3c61387e-cde2-44ed-a290-03761a7c2628" />

# RESULT
Thus, the Python program to print the size of a dictionary using getsizeof() from the sys module is successfully done.
