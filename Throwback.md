## Powershell Commands


Importing modules

```powershell
Import-Module Module 

or . .\Module.ps1
```

Get-ADDomain

```powershell
Get-ADDomain | Select-Object NetBIOSName, DNSRoot, InfrastructureMaster

```

Get-ADForest

```powershell
Get-ADForest | Select-Object Domains
```

Get-ADTrust 

```powershell
Get-ADTrust -Filter * | Select-Object Direction,Source,Target
```