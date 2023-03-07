# [Python-VScode](https://learn.microsoft.com/zh-cn/training/modules/python-install-vscode/3-exercise-install-python3?pivots=windows)

OS: Windows 10
IDE: VS-code 

## Step_0: Check if Python is installed in Windows-10
Bash/CMD -> 
    python --version

Case1: Python is already successfully installed in Windows-10
output:
    Python 3.11.2

Case2: Python is not yet installed in Windows-10
output:
    Error: Python is not found

## Step_1: Install Python3 in Windows-10
Start -> Microsoft Store -> Python 
Select the latest version of Python, click "Get"

## Step_2: Install Visual Studio Code 
[Download Visual Studio Code](https://code.visualstudio.com/Download)

## Step_3: Install Python Extensions in VScode 
VScode -> Extensions -> Python IntelliSense (Pylance) -> Install 

## Step_4: Create the first Python program in VScode

4.1 Create an empty folder 
Bash -> 
mkdir hello-world 
cd hello-world 
code .    # Open Visual Studio Code in that folder 

4.2 Create a Python script
Under the visual panel of HELLO-WORLD, click "New File"
Type the name for the file: hello.py

4.3 Edit the Python script 
In the editor panel, write python code:
    print("Hello, World!")

4.4 Save the Python script 
Ctrl+S

4.5 Run 
View -> Integrated Terminal -> 
Bash ->
Python hello.py






