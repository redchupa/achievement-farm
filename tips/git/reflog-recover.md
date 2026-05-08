# Recover a lost commit via reflog

Reflog tracks HEAD movements even after resets and rebases.

```bash
git reflog && git checkout SHA
```
