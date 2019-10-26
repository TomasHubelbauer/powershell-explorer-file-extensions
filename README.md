# Show or Hide File Extensions in Explorer using PowerShell

Show:

```powershell
reg add HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced /v HideFileExt /t REG_DWORD /d 0 /f
```

Hide:

```powershell
reg add HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced /v HideFileExt /t REG_DWORD /d 1 /f
```

Source: https://superuser.com/a/666895/490452
