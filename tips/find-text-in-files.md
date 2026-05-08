# Find text across files recursively

Native grep without installing ripgrep.

```powershell
Get-ChildItem -Recurse -Include *.ps1,*.md | Select-String -Pattern 'TODO'
```
