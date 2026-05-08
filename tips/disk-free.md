# Show free space per drive

One line, no calculator needed.

```powershell
Get-PSDrive -PSProvider FileSystem | Select-Object Name,Free,Used
```
