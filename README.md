---
description: A tool to migrate an App-V 4.6 package to App-V 5.1
---

# Welcome!

## Getting started

 To be able to install and use the "AppVMigrationTool" tool, you will need:

* PowerShell 3.0 or higher  
* .NET framework 3.5 or higher 
* App-V Sequencer 5.0 installed on your computer

Check **before executing the binary** file that the _PowerShell commandlets_ are available. Use 32-bit PowerShell!

```text
Get-Module -Name AppvPkgConverter
Get-command *appvlegacy*
```

{% hint style="warning" %}
If you use Windows 10, please install the [Windows ADK](https://docs.microsoft.com/en-us/windows-hardware/get-started/adk-install)
{% endhint %}

## Install on Windows 10

Download this [zip file](https://github.com/julienbriault/AppVMigrationTool/releases/download/0.0.4/AppVMigrationTool.zip) and launch **AppVMigrationTool.exe** with administrator rights.

