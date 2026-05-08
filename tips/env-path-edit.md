# Append a directory to the user PATH

Persists across sessions, no admin needed.

```powershell
[Environment]::SetEnvironmentVariable('Path', [Environment]::GetEnvironmentVariable('Path','User') + ';C:\tools', 'User')
```
