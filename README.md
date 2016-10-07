# Desired State Configuration - Developer machine 

A DSC configuration for setting up a developer machine with a base set of packages.

## Pre-requisites

WMF 5 must be downloaded and installed on machine prior to running this script. If you're on Windows 10 with latest updates, you're good to go. If not, download it from <a href="https://www.microsoft.com/en-us/download/details.aspx?id=50395">Microsoft; here </a>.

When WMF5 is installed install this module

### Run powershell as administrator
```powershell
Find-Module PackageManagementProviderResource|Install-Module
```
## Configure your modules
To add / modify what would be installed on your computer, open DeveloperMachineConfiguration.psd1 and modify required packages

#### DeveloperMachineConfiguration.psd1
```powershell
<# Todo #>
```

## Compiling
If this is your first time running the configuration, you should configure your Local configuration manager to allow reboots (as some of the packages will require a reboot). When this is done, you can compile and run the configuration and modify it as you please.

### Enable LCM to automatic reboot
```powershell
<# Todo #>
```

### Compile and run configuration 
```powershell
<# Todo #>
```
