# Creating Organizational Unit for Active Directory w/ PowerShell Script

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

### 2. Run Script

- Open PowerShell as Administrator.
- Paste the Script and run it.
- Verify that the OU has been created in the Active Directory Users and Computers app.

## Outcome

Successfully automated the creation of an OU using PowerShell.