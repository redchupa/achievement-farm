# Find the largest files in a tree

Locate space hogs without installing anything.

```powershell
Get-ChildItem -Recurse -File | Sort-Object Length -Descending | Select-Object -First 10 FullName
```
