### TRACKING PATH CHANGES
Versioning file removes and path changes

```
git rm [file]
```
Delete the file from project and stage the removal for commit

---

```
git mv [existing-path] [new-path]
```
Change an existing file path and stage the move

---

```
git log --stat -M
```
Show all commit logs with indication of any paths that moved

---