# Get-TaskPermissions
A PowerShell script for detailed visibility into scheduled tasks, highlighting user permissions and potential security configurations.

## Usage
(Recommended) Default usage displays only items where the current user has the capability to modify the file, providing a focused analysis on potential security or administrative actions. 
```
.\Get-TaskPermissions.ps1
```
- -All: Runs the script to display all elements, ignoring default limitations.
- -cls: Clears the console for a fresh view.
- -Debug: Displays debug information.

![image](https://github.com/selmankon/Get-TaskPermissionChecker/assets/12685802/95f5621d-8adb-4817-905e-4739524ed4e7)


