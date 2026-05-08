# Show the top 5 CPU-using processes

Quick health check when the fan spins up.

```powershell
Get-Process | Sort-Object CPU -Descending | Select-Object -First 5 ProcessName,CPU,Id
```
