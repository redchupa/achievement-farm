# List running services

Filter Get-Service the way you actually want.

```powershell
Get-Service | Where-Object Status -eq 'Running' | Sort-Object DisplayName | Select-Object Name,DisplayName
```
