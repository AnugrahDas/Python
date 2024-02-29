# Python
Programming in Python
Write python program to print first letter of your name 
a) Example: Peter
               *      *
               *             *
               *              *
               *      *
               *
               *
               *
Anugrah Das 2210997040
Code:
pattern=["  *  ",
         " *  *",
         "*****",
         "*   *",
         "*   *"]
for line in pattern:
b) Print your name by using for loop
Code:
name = "Anugrah"
for letter in name:
    print("letter")
c) check the user name is palindrome or not
Code:
name="Anugrah"
if name.lower()==name[::-1].lower():
    print("The name is a palindrome")
else:
    print("The name is not a palindrome")
