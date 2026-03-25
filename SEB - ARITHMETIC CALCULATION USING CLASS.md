# Exp.No:20 SEB - ARITHMETIC CALCULATION USING CLASS
# AIM
To write a Python program to perform addition and division operations using a class. The class should be named Saveetha, and the function names should be setvalues (to set a and b values), add, and div. The program should handle the following cases: choice 1 → Perform addition choice 2 → Perform division choice 0 → Exit For other choices, print 'Invalid choice'

# ALGORITHM
Begin the program. Create a class Saveetha. Define the following methods inside the Saveetha class: init(self): Initializes a and b to zero. setvalues(self, a, b): Sets the values of a and b. add(self): Performs the addition operation. div(self): Performs the division operation. If b is zero, returns an error message for division by zero. Create a main() function. Take input from the user for the values of a and b using setvalues(a, b) method. Use a while True loop to repeatedly ask the user for a choice: If the choice is 1, call the add() method and print the result. If the choice is 2, call the div() method and print the result. Handle division by zero. If the choice is 0, print "Exiting!" and exit the loop. If the choice is not 1, 2, or 0, print "Invalid choice". Terminate the program.

# PROGRAM
~~~


class saveetha:
    def add(self,a,b):
        return a+b
    def div(self,a,b):
        return a//b
c=saveetha()
a=int(input())
b=int(input())
choice=1
while choice!=0:
    choice=int(input())
    if choice==1:
       print("Result: ",c.add(a,b))
    elif choice==2:
       print("Result: ",c.div(a,b))
    else:
        print("Exiting!")
~~~
# OUTPUT
<img width="747" height="458" alt="image" src="https://github.com/user-attachments/assets/2b819618-86b4-4319-ac21-e69ca30b5aab" />

# RESULT
Thus the To write a Python program to perform addition and division operations using a class. The class should be named Saveetha, and the function names should be setvalues (to set a and b values), add, and div is successfully verified.
