Automates the installation of storj-bridge for Windows only
<br/>
<br/>INSTRUCTIONS:
<br/>1.) Download ZIP of storjshare-bridge-automate
<br/>2.) Extract ZIP
<br/>3.) Double-click `install.bat`
<br/>4.) (if prompted) Click Yes on the User Account Control (UAC) screen
<br/>5.) Reboot when completed
<br/>6.) Double-click `install.bat`
<br/>7.) Installation should be completed.  Configure storj-bridge as needed.
<br/>
<br/>COMPATIBILITY:
<br/>   -PowerShell Version 2 or newer
<br/>   -Administrator rights are required
<br/>   -Client OS: Windows 7 or newer
<br/>   -Server OS: Windows 2008 or newer
<br/>
<br/>ADVANCED FUNCTIONALITY: (TBD - may be removed!!!!)
<br/>  Examples:
<br/>  To deploy silently use the following command
<br/>  ./automate_storj_cli.ps1 -silent
<br/>
<br/>  To install service use the following command
<br/>  ./automate_storj_cli.ps1 -installsvc -svcname storjshare -datadir C:\storjshare -password 4321
<br/>
<br/>  To remove service use the following command
<br/>  ./automate_storj_cli.ps1 -removesvc -svcname storjshare
<br/>
<br/>  To disable UPNP
<br/>  ./automate_storj_cli.ps1 -noupnp
<br/>