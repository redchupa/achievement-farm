# Delete branches already merged into main

Tidy up local branches whose work is already in main.

```bash
git branch --merged main | grep -v main | xargs git branch -d
```
