# Hash every file in a folder

Quick integrity snapshot before/after a sync.

```powershell
Get-ChildItem -Recurse -File | Get-FileHash -Algorithm SHA256 | Select-Object Hash,Path
```
