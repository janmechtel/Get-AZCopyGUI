# AZCopy.exe downloader with resume GUI
## A simple GUI wrapper for AZCopy.exe to simplify the process of downloading (large) files from azure blobstorage and resuming them

A simple GUI wrapper for AZCopy.exe to simplify the process of downloading (large) files from azure blobstorage and resuming them.
** Attribution:**

This is based on https://github.com/cgoosen/Get-AZCopyGUI 

**Requirements:**

This script will work natively in PowerShell 2.0+
This script requires the Microsoft Azure AZCopy Tool with default installation path - [get it here](https://docs.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10)

**Usage:**
There are no parameters or switches, simply execute the script: .\Get-AZCopyGUI.ps1

When using the Verbose option, a log file is named AzCopyVerbose.log will be created in %LocalAppData%\Microsoft\Azure\AzCopy if no "Log Location" is specified.

**Screenshots:**

![alt text](https://www.cgoosen.com/wp-content/uploads/2015/05/Capture.png)
