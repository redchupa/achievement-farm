# Kill the process holding a TCP port

Useful when a dev server refuses to release the port.

```powershell
Get-NetTCPConnection -LocalPort 3000 | ForEach-Object { Stop-Process -Id $_.OwningProcess -Force }
```
