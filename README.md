# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.
```
mkdir %sec%\Desktop\MyLab
```
![image](https://github.com/user-attachments/assets/aa3292a2-6926-4f1a-92a0-cd6d9953826f)


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
```
cd %sec%\Desktop\MyLab
touch MyFile.txt
```
![image-1](https://github.com/user-attachments/assets/885befb3-0cc0-4586-bf72-67edf5f9aa35)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
dir %sec%\Desktop\MyLab
```
![image-2](https://github.com/user-attachments/assets/09ae5c58-d5b1-4153-805d-74ca8d7ce224)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
mkdir %sec%\Desktop\Backup
cp MyFile.txt %sec%\Desktop\Backup
```
![image-3](https://github.com/user-attachments/assets/dcccbcce-f338-4180-8690-f7ddb7bf6a44)
![image-4](https://github.com/user-attachments/assets/62ec2861-d99b-46fc-96d7-88fba712ac4c)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
```
mv MyFile.txt MyLab\Documents
```
![image-5](https://github.com/user-attachments/assets/2aab07a8-830c-45e6-abc3-d43b5d68d97b)


## COMMAND AND OUTPUT


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

### BackupScript.bat
```
@echo off
mkdir %sec%\Desktop\DocBackup
copy %sec%\Documents\*.docx %sec%\Desktop\DocBackup
del %sec%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!
```




## OUTPUT

![image-6](https://github.com/user-attachments/assets/4ea25ccb-6185-4e0e-a73c-4a44010ef219)



# RESULT:
The commands/batch files are executed successfully.







# RESULT:
The commands/batch files are executed successfully.

