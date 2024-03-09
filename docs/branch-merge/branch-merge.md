### BRANCH & MERGE

Isolating work in branches, changing context, and integrating changes.

```
git branch
```
List your branches. a * will appear next to the currently active branch

---

```
git branch [branch-name]
```
Create a new branch at the current commit

---

```
git checkout
```
Switch to another branch and check it out into your working directory

---

```
git merge [branch]
```
Merge the specified branch’s history into the current one

---

```
git log
```
Show all commits in the current branch’s history

---

```
git branch -d localBranchName
```
Delete branch locally

---

```
git push origin --delete remoteBranchName
```
Delete branch remotely. Example: `git push origin --delete fix/authentication` or `git push origin :fix/authentication`

---

```
git fetch -p
```
**Try to synchronize your branch list using**

The `-p` flag means "prune". After fetching, branches which no longer exist on the remote will be deleted.

---
