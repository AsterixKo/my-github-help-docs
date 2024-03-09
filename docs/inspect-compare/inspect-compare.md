### INSPECT & COMPARE
Examining logs, diffs and object information

```
git log
```
Show the commit history for the currently active branch

---

```
git log branchB..branchA
```
Show the commits on branchA that are not on branchB

---

```
git log --follow [file]
```
Show the commits that changed file, even across renames

---

```
git diff branchB...branchA
```
Show the diff of what is in branchA that is not in branchB

---

```
git show [SHA]
```
Show any object in Git in human-readable format

---