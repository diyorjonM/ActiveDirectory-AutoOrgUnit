# Creating Organizational Unit for Active Directory w/ PowerShell Script

### Watch Me Do This Lab HERE

https://www.loom.com/share/021f826ddcf5421abc95d31f130ab95c 

## Project Overview

This lab documents the use of a PowerShell script to automate the creation of an Organizational Unit (OU) on Service Now.

The purpose of this project was to:

- Create a PowerShell Script.
- Create a OU with a script.

## Environment Details

| Component              | Configuration                         |
|------------------------|---------------------------------------|
| Cloud Provider         | AWS                                   |
| Compute Service        | Amazon EC2                            |
| Operating System       | Windows Server Base 2025              |
| Directory Service      | Active Directory Domain Services      |
| Terminal               | PowerShell                            |

## Steps

### 1. Create PowerShell Script

- Open File Explorer, go to C: drive and create a Scripts folder.
- Select New > Text Document to create a .txt file.
- Paste the script into the .txt file, select save as and add the ".ps1" extension to save as a PowerShell file.

<img width="1116" height="702" alt="Screenshot 2026-04-14 at 8 34 01 PM" src="https://github.com/user-attachments/assets/e4d6eacc-e3cc-4b75-86f9-e1b888897a9a" />


### 2. Run Script

- Open PowerShell as Administrator.
- Paste the Script and run it.
  
<img width="549" height="371" alt="Screenshot 2026-04-14 at 8 34 45 PM" src="https://github.com/user-attachments/assets/97ee63ab-54f5-469a-b118-6d7e75ae71ca" />

<img width="969" height="626" alt="Screenshot 2026-04-14 at 8 34 58 PM" src="https://github.com/user-attachments/assets/e10768c4-7502-4ec5-92ca-004017dc23b1" />

- Verify that the OU has been created in the Active Directory Users and Computers app.

<img width="753" height="520" alt="Screenshot 2026-04-14 at 8 35 15 PM" src="https://github.com/user-attachments/assets/8136869c-5581-466f-8389-b10bb2d7bdec" />

## Outcome

Successfully automated the creation of an OU using PowerShell.
