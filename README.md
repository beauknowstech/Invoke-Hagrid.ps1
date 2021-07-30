# Invoke-Hagrid.ps1

This is a very crude and basic Powershell wrapper for Rubeus. All credit goes to https://github.com/GhostPack/Rubeus



Usage:
```
   Import-Module .\Invoke-Hagrid.ps1
   OR
   . .\Invoke-Hagrid.ps1
   Invoke-Hagrid -command 'kerberoast /format:hashcat /outfile:C:\Temp\allKERB.txt'
   ```
