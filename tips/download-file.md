# Download a file with progress

No need for curl or wget on a fresh box.

```powershell
Invoke-WebRequest -Uri 'https://example.com/file.zip' -OutFile file.zip
```
