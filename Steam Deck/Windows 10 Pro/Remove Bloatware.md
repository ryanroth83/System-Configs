1. Check to see the entire spectrum of system bloatware using the following command:

‘DISM /Online /Get-ProvisionedAppxPackages | select-string Packagename’


2. You should now see a complete list of installed apps. We can now use these package names to begin removing what we want. To remove them, use the following command:

‘ DISM /Online /Remove-ProvisionedAppxPackage /PackageName:PACKAGENAME‘

-OR-

[Windows 10 Debloater](https://github.com/Sycnex/Windows10Debloater)