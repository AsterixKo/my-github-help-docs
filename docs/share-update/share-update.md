### SHARE & UPDATE
Retrieving updates from another repository and updating local repos

```
git remote add [alias] [url]
```
Add a git URL as an alias

---

```
git fetch [alias]
```
Fetch down all the branches from that Git remote

---

```
git merge [alias]/[branch]
```
Merge a remote branch into your current branch to bring it up to date

---

```
git push [alias] [branch]
```
Transmit local branch commits to the remote repository branch

---

```
git push -f
```
Is short for git push --force. It forces a push when otherwise git would reject your git push because you changed your repo history in your pushing repository. Forced pushes also let you overwrite someone else's commits which have been pushed after your last pull.
[Difference between git push and git push -f](https://stackoverflow.com/questions/44678942/difference-between-git-push-and-git-push-f)

---

```
git pull
```
Fetch and merge any commits from the tracking remote branch

---