# Bisect a regression automatically

Let Git binary-search across history using a script as oracle.

```bash
git bisect start && git bisect bad && git bisect good SHA && git bisect run ./test.sh
```
