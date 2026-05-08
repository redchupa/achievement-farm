# Time a command execution

Built-in alternative to bash time.

```powershell
Measure-Command { ./build.ps1 } | Select-Object TotalSeconds
```
