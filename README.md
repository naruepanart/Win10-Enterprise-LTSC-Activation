# Win10-Enterprise-LTSC-Activation

## Location

```
C:\Windows\System32\spp\tokens\skus
```

## CMD
```
cscript.exe %windir%\system32\slmgr.vbs /rilc
cscript.exe %windir%\system32\slmgr.vbs /upk >nul 2>&1
cscript.exe %windir%\system32\slmgr.vbs /ckms >nul 2>&1
cscript.exe %windir%\system32\slmgr.vbs /cpky >nul 2>&1
cscript.exe %windir%\system32\slmgr.vbs /ipk M7XTQ-FN8P6-TTKYV-9D4CC-J462D
cscript.exe %windir%\system32\slmgr.vbs /skms kms.digiboy.ir
cscript.exe %windir%\system32\slmgr.vbs /ato
```
