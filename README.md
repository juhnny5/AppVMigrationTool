<p align="center">
  <img src="https://raw.githubusercontent.com/julienbriault/AppVMigrationTool/master/icones/github-icone.png"/></p>
 </p>

# App-V Migration Tool
A tool to migrate an Microsoft App-V 4.6 package to App-V 5.1

### Programming context
The programming of this graphic tool is part of a study project at the ENI school in Nantes, France.
The purpose of this tool is to simplify the conversion from an App-V 4.6 package to a 5.1 package without going through the command line.

### Prerequisites
To be able to install and use the "AppVMigrationTool" tool, you will need:
- PowerShell 3.0 or higher  
- .NET framework 3.5 or higher 
- App-V Sequencer 5.0 installed on your computer

if you use Windows 10, please install the [Windows ADK](https://docs.microsoft.com/en-us/windows-hardware/get-started/adk-install)

Check **before executing the binary** file that the *PowerShell commandlets* are available. Use 32-bit PowerShell!

```powershell
Get-Module -Name AppvPkgConverter
Get-command *appvlegacy*
```

### Install on Windows 10

Download this [zip file](https://github.com/julienbriault/AppVMigrationTool/releases/download/0.0.4/AppVMigrationTool.zip) and launch **AppVMigrationTool.exe** with administrator rights. 

### What can I do with this tool?
#### Convert an package App-V 4.6 to App-V 5.1
<p align="center">
  <img src="https://raw.githubusercontent.com/julienbriault/AppVMigrationTool/master/images/main-screenshot-appvmigration-tool.png"/></p>
 </p>
 
#### Test an package App-V 4.6 before converting
<p align="center">
  <img src="https://raw.githubusercontent.com/julienbriault/AppVMigrationTool/master/images/test-screenshot-appvmigration-tool.png"/></p>
 </p>

 ### Live preview
 #### Convert an package App-V 4.6 to App-V 5.1
 <p align="center">
  <img src="https://raw.githubusercontent.com/julienbriault/AppVMigrationTool/master/images/convertpackage.gif"/></p>
 </p>

 
