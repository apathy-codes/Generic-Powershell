# Generic-Powershell
Most scripts require admin privileges

# Bypass confirmations:
powershell.exe -ExecutionPolicy Bypass -File .\file.ps1

# Powershell cannot run scripts
Set-ExecutionPolicy Unrestricted

Set-ExecutionPolicy RemoteSigned
