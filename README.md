# Activate Windows 10/11 Enterprise LTSC

Supported Versions:

- Windows 11 Enterprise LTSC 2024
- Windows 10 Enterprise LTSC 2021
- Windows 10 Enterprise LTSC 2019

## 1. Copy Required Files

Copy these folders to the correct location:

- csvlk-pack
- EnterpriseS

Destination Path:

```
C:\Windows\System32\spp\tokens\skus
```

## 2. Run Activation Commands (Admin CMD)

```cmd
cscript.exe %windir%\system32\slmgr.vbs /rilc
cscript.exe %windir%\system32\slmgr.vbs /upk >nul 2>&1
cscript.exe %windir%\system32\slmgr.vbs /ckms >nul 2>&1
cscript.exe %windir%\system32\slmgr.vbs /cpky >nul 2>&1
cscript.exe %windir%\system32\slmgr.vbs /ipk M7XTQ-FN8P6-TTKYV-9D4CC-J462D
cscript.exe %windir%\system32\slmgr.vbs /skms kms.digiboy.ir
cscript.exe %windir%\system32\slmgr.vbs /ato
```

Notes:

- /skms parameter sets the Key Management Service (KMS) server.

- If kms.digiboy.ir doesn’t work, try one of these alternatives:

```
54.223.212.31
kms.cnlic.com
kms.chinancce.com
kms.ddns.net
franklv.ddns.net
k.zpale.com
m.zpale.com
mvg.zpale.com
kms.shuax.com
kensol263.imwork.net:1688
kms.loli.best
kms.vudy.net
```
