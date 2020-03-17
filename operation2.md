1. checkout `operation2` branch
```
git checkout operation2
```
2. rebase onto `operation` branch
```
git rebase operation
# First, rewinding head to replay your work on top of it...
# Fast-forwarded operation2 to operation.
```
3. create, add, commit and push `operation2.md` file
```
git add operation2.md
git commit -m "add operation2.md"
git push origin HEAD
```
