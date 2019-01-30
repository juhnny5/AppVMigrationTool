# Start-up guide!

![](https://raw.githubusercontent.com/julienbriault/AppVMigrationTool/master/icones/github-icone.png)

### Programming context

The programming of this graphic tool is part of a study project at the ENI school in Nantes, France. The purpose of this tool is to simplify the conversion from an App-V 4.6 package to a 5.1 package without going through the command line.

### Getting started

Find the full start-up guide [here](https://julien-briault.gitbook.io/appvmigrationtool/).

To be able to install and use the "AppVMigrationTool" tool, you will need:

* PowerShell 3.0 or higher  
* .NET framework 3.5 or higher 
* App-V Sequencer 5.0 installed on your computer

Check **before executing the binary** file that the _PowerShell commandlets_ are available. Use 32-bit PowerShell!

```text
Get-Module -Name AppvPkgConverter
Get-command *appvlegacy*
```

If you use Windows 10, please install the [Windows ADK](https://docs.microsoft.com/en-us/windows-hardware/get-started/adk-install).

### Install on Windows 10

Download this [zip file](https://github.com/julienbriault/AppVMigrationTool/releases/download/0.0.4/AppVMigrationTool.zip) and launch **AppVMigrationTool.exe** with administrator rights.

### How to use ?

Follow the following link to learn how to use this tool: [Usage](https://github.com/julienbriault/AppVMigrationTool/blob/master/usage.md)
