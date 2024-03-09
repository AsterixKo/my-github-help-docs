### STAGE & SNAPSHOT

```
git status
```
Show modified files in working directory, staged for your next commit

---

```
git add [file]
```
Add a file as it looks now to your next commit (stage)

---

```
git reset [file]
```
Unstage a file while retaining the changes in working directory

---

```
git diff
```
Diff of what is changed but not staged

---

```
git diff --staged
```
Diff of what is staged but not yet commited

---

```
git commit -m "[descriptive message]"
```
Commit your staged content as a new commit snapshot

---

```
git commit -m "[descriptive message #issueNumber]"
```
Commit your staged content as a new commit snapshot pointing the issueNumber on GitHub. Example #746

---

```
git commit –amend -m "message corrected"
```
Correct commit message

---