# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript
# NAME :A.HALIMA HARISHA
# REGISTER NO :212224040094

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
```
mkdir %userprofile%\Desktop\MyLab
```
![image](https://github.com/user-attachments/assets/202ae4c8-b593-42d2-94ff-db2d8e05390a)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
cd %userprofile%\Desktop\MyLab
```

![image](https://github.com/user-attachments/assets/eaa4321f-82d2-4e66-9290-2485fc15ad7f)

![image](https://github.com/user-attachments/assets/158752d3-c581-4611-bab6-650261eb86df)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
dir %userprofile%\Desktop\MyLab
```
![image](https://github.com/user-attachments/assets/860f84f3-95d2-436b-baf8-6030d12abdc7)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup

copy MyFile.txt %userprofile%\Desktop\Backup
```
![image](https://github.com/user-attachments/assets/f2866c36-b83a-47c3-abd9-ce3b627be001)
![image](https://github.com/user-attachments/assets/92333dd8-2a9d-4319-b734-8f5010dafd5e)


## COMMAND AND OUTPUT
```
mv Myfile.txt %userprofile%\Documents
```
![image](https://github.com/user-attachments/assets/f521b669-3e93-467b-adc0-f18b8b64493d)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
Modify the script to delete files with the ".docx" extension from the "Documents" folder after creating the backup

  ```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```




## OUTPUT


![image](https://github.com/user-attachments/assets/4f7905af-8082-41fc-8dc3-bd2e5a1da627)



# RESULT:
The commands/batch files are executed successfully.

