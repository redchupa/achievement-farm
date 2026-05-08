# Embed git branch in the prompt

Two lines in your profile and you have context.

```powershell
function prompt { 'PS ' + (Get-Location).Path + ' [' + (git branch --show-current) + '] > ' }
```
