This is Powershell script intended for fresh Windows OS instalation to get the basic application installed automatically.

Execute with folowing command in PowerShell:

**Set-ExecutionPolicy Bypass -Scope Process -Force; iex (iwr 'https://raw.githubusercontent.com/rico1202/install-apps/refs/heads/main/install.ps1' -UseBasicParsing).Content**

OR

download and exacute with **installApps.bat**

Currently the list of installed apps is folowing:
  * Notepad++
  * VLC
  * Acrobat Reader
  * 7zip
  * HWMonitor
