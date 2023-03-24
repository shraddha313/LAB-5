# LAB-5
IT 314 Software Engineering
Lab 5
Name: doshi shraddha vimalbhai
Student ID: 202001278
Static Code Analysis of a git repository using mypy tool
Reference Git Repository:https://github.com/SharwariSM/Hostel-management-system
Reference Git Repository:https://github.com/shraddha313/hiiii/tree/main/Lab-5_202001149
Reference Git Repository:https://github.com/shraddha313/hiiii/tree/main/Lab-5_202001149
mypy tool:
mypy is an open-source static type checker for Python.
It supports type annotations for function arguments, return values, and variables.
It can also check for common type-related errors such as type mismatches, invalid method calls, and incorrect argument types.
mypy supports various types of annotations including built-in types like str, int, float, etc., user-defined classes, generic types, and union types.
It also provides options to customize the checking process, ignore certain files, and suppress specific error messages

Process:
open vscode
install mypy using command: python -m pip install mypy
clone the git repository
then run the file 

1) first repo 
![image](https://user-images.githubusercontent.com/77456124/227494544-75d7db00-4dc7-493c-a8bf-f188be47a741.png)
first file main.py : no error 
second file : hostel.py  : imcomatible import error 

2) second repo 

first file hi.py 
![image](https://user-images.githubusercontent.com/77456124/227495052-5e6db3b5-89bd-492d-bc9b-b6099a58c53b.png)
error: missing stub error 

second file .hii2.py
![image](https://user-images.githubusercontent.com/77456124/227495405-f7c16091-9bc0-4d23-8ab0-22371b6563c6.png)
error: missing stub error 

third file : test.py 
![image](https://user-images.githubusercontent.com/77456124/227495602-9c7b663c-d4c7-4eb7-9e5e-cd2ac6a70f34.png)
error : name error
module error 
import error 

fourth file : sh.py

