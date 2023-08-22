# Default foler/path

## Windows
### Answer files/Unattend files
```
C:\Unattend.xml
C:\Windows\Panther\Unattend.xml
C:\Windows\Panther\Unattend\Unattend.xml
C:\Windows\system32\sysprep.inf
C:\Windows\system32\sysprep\sysprep.xml
```

### Powershell history
`%userprofile%\AppData\Roaming\Microsoft\Windows\PowerShell\PSReadline\ConsoleHost_history.txt`

### Startup folder
```
C:\Users\<your_username>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp
```

### Active Directory

#### SYSVOL
`C:\Windows\SYSVOL\sysvol\`

#### Ntds.dit
`C:\Windows\NTDS\ntds.dit`

`C:\Windows\System32\config\SYSTEM`

`C:\Windows\System32\config\SECURITY`

#### Security Account Manager (SAM)
`c:\Windows\System32\config\sam`

`\\?\GLOBALROOT\Device\HarddiskVolumeShadowCopy1\windows\system32\config\sam`

Key decryption:

`c:\Windows\System32\Config\system`

`\\?\GLOBALROOT\Device\HarddiskVolumeShadowCopy1\windows\system32\config\system`

#### Check LAPS
`C:\Program Files\LAPS\CSE`


## Linux


## Software

### Internet Information Services (IIS)
```
C:\inetpub\wwwroot\web.config
C:\Windows\Microsoft.NET\Framework64\<version>\Config\web.config
```

`C:\inetpub\wwwroot`

### MSBuild
`c:\Windows\Microsoft.NET\Framework\<version>\MSBuild.exe`

## Cloud

### Amazon Web Services

The plain-text credentials existed on EC2 instance.

`%UserProfile%\.aws\credentials`

`$HOME/.aws/credentials`