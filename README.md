# Project-13
Program 13: WAP to accept a name from a user. Raise and handle appropriate exceptions if the text entered by the user contains digits and/or special characters.
code=name=input("enter a name ")

try:

if name.isalpha():

print("This is correct name")

else:

raise Exception (" There is NameErrror")

except Exception as e:

print(e)
