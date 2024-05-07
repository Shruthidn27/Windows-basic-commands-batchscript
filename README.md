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


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab
![image](https://github.com/Shruthidn27/Windows-basic-commands-batchscript/assets/138849783/5a68a9b0-03b1-426e-8aea-e92265171368)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab
![image](https://github.com/Shruthidn27/Windows-basic-commands-batchscript/assets/138849783/c7db5377-8e15-4d44-9722-c9df799f7393)
![image](https://github.com/Shruthidn27/Windows-basic-commands-batchscript/assets/138849783/01954320-1b99-40ba-80ab-92a881c3d436)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
%userprofile%\Desktop\MyLab
![image](https://github.com/Shruthidn27/Windows-basic-commands-batchscript/assets/138849783/245da0e6-de71-4fd4-9b18-1f755d220e5e)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup1
mkdir %userprofile%\Desktop\Backup
![image](https://github.com/Shruthidn27/Windows-basic-commands-batchscript/assets/138849783/68655b8d-5240-4efd-961c-751f92c061e3)

![image](https://github.com/Shruthidn27/Windows-basic-commands-batchscript/assets/138849783/5aa6d619-e469-4f16-a104-490d6a9dbd45)



## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents

![image](https://github.com/Shruthidn27/Windows-basic-commands-batchscript/assets/138849783/ca3b69d2-a01b-454b-a105-e0c3c20a1917)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!


## OUTPUT

![image](https://github.com/Shruthidn27/Windows-basic-commands-batchscript/assets/138849783/ed1c90ea-b83a-4f6f-a3b2-854651f6d5b4)





# RESULT:
The commands/batch files are executed successfully.

