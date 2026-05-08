# List saved Wi-Fi profiles

Recover the SSIDs your laptop has connected to.

```powershell
netsh wlan show profiles | Select-String 'All User Profile'
```
