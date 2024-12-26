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
![Screenshot_20241227-014049_Chrome](https://github.com/user-attachments/assets/88def035-0bd0-421c-ae07-a947e93f3982)
