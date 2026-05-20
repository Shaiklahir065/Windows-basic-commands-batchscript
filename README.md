# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
Remove the directory "my-folder"
```
>mkdir my-folder
>rmdir my-folder
```

<img width="521" height="95" alt="image" src="https://github.com/user-attachments/assets/eb493ac9-9497-408c-8df8-578ce48382ea" />



## COMMAND AND OUTPUT

Create the file Rose.txt
```
COPY CON Rose.txt
A clock in a office can never get stolen
Too many employees watch it all the time
^Z
1 file(s) copied
dir Rose.txt
```

<img width="758" height="375" alt="image" src="https://github.com/user-attachments/assets/8288528b-2cf2-45f4-9376-2bc0d1d32df8" />




## COMMAND AND OUTPUT
Create the file hello.txt using echo and redirection

```
echo “hello world” > hello.txt
type hello.txt
```
<img width="580" height="103" alt="image" src="https://github.com/user-attachments/assets/375f410a-6b6e-4f12-b086-192af23990cf" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
```
copy hello.txt hello1.txt
```
<img width="508" height="79" alt="image" src="https://github.com/user-attachments/assets/75178717-97b1-4698-ab4c-23b8693e90a2" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

```
del hello1.txt
```
<img width="422" height="58" alt="image" src="https://github.com/user-attachments/assets/0bb5f4f8-203a-44af-8864-e60be66994c4" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

```
dir hello1.txt
```
<img width="460" height="135" alt="image" src="https://github.com/user-attachments/assets/7e88df7f-23c2-4ffb-8ee4-ce676fd7da68" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

```
assoc | more
```
<img width="532" height="788" alt="image" src="https://github.com/user-attachments/assets/a8f16bf8-c1f3-47db-91e2-dd9529b5c610" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

```
fc hello.txt Rose.txt
```
<img width="550" height="203" alt="image" src="https://github.com/user-attachments/assets/2d19e64b-e312-423d-925e-dbc29951443e" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="575" height="142" alt="image" src="https://github.com/user-attachments/assets/bb7d47df-710e-414d-bd3e-b3beb2d82e3f" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="836" height="286" alt="image" src="https://github.com/user-attachments/assets/f0bbd709-5c5c-47ad-86df-643e997eda41" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="904" height="244" alt="image" src="https://github.com/user-attachments/assets/8cc1afdc-6fa9-46fd-b23f-d8d47074c8bf" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="735" height="142" alt="image" src="https://github.com/user-attachments/assets/de62f124-d372-4ae8-845b-0c3d3b444a24" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="853" height="473" alt="image" src="https://github.com/user-attachments/assets/be72abad-f0a1-4446-ab40-472444e71326" />


# RESULT:
The commands/batch files are executed successfully.

