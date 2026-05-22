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

<img width="577" height="167" alt="Screenshot 2026-05-21 090603" src="https://github.com/user-attachments/assets/83777789-1ee3-441f-9340-350e0a41fa6c" />

Create a directory named "my-folder"
## COMMAND AND OUTPUT
<img width="323" height="40" alt="image" src="https://github.com/user-attachments/assets/2048c2c4-fb9c-4d8e-a370-07194194e12c" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="668" height="393" alt="Screenshot 2026-05-21 090802" src="https://github.com/user-attachments/assets/5b313d79-29dd-40c1-9b81-f7c892ad4817" />

Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="635" height="116" alt="Screenshot 2026-05-21 090922" src="https://github.com/user-attachments/assets/9e2f546e-9080-4aa1-9079-4b4ef612c1b8" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="575" height="145" alt="Screenshot 2026-05-21 091010" src="https://github.com/user-attachments/assets/183bf3ec-c207-42f7-8b04-a1b63c9e2615" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="527" height="245" alt="Screenshot 2026-05-21 091222" src="https://github.com/user-attachments/assets/4588c4b4-fa69-42a3-9d06-434150b761c1" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="480" height="826" alt="Screenshot 2026-05-21 091301" src="https://github.com/user-attachments/assets/f0f3e384-bccb-4c96-b04f-b903f6c1edf3" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="467" height="167" alt="Screenshot 2026-05-21 091501" src="https://github.com/user-attachments/assets/7470f97a-1312-427c-a400-d35bd0235ce1" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="467" height="167" alt="Screenshot 2026-05-21 091501" src="https://github.com/user-attachments/assets/1d3bdb75-da2d-4ee1-9178-1f4e72864fad" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".



<img width="363" height="85" alt="Screenshot 2026-05-21 091850" src="https://github.com/user-attachments/assets/125be04d-9505-4853-a644-9c3bb6e0fc3f" />




## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



<img width="776" height="300" alt="Screenshot 2026-05-21 091604" src="https://github.com/user-attachments/assets/afbf20e3-4957-4aa4-a11f-82b6f5b83909" />

## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.


<img width="565" height="215" alt="Screenshot 2026-05-21 092309" src="https://github.com/user-attachments/assets/dc319a2a-98b5-4e36-8b13-ae345461a80b" />



## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

<img width="492" height="166" alt="Screenshot 2026-05-21 092420" src="https://github.com/user-attachments/assets/7e1464f1-8429-4168-97c6-00eef47ee755" />


## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


<img width="531" height="208" alt="Screenshot 2026-05-21 092552" src="https://github.com/user-attachments/assets/96c9fbb3-d9ab-4996-9509-da0e67e26d7c" />

## OUTPUT


<img width="522" height="387" alt="Screenshot 2026-05-21 092701" src="https://github.com/user-attachments/assets/5ab05385-c091-4bb2-a999-65f0dab7906d" />


# RESULT:
The commands/batch files are executed successfully.

