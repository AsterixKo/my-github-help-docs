### GIT TAGS
Like most VCSs, Git has the ability to tag specific points in a repository’s history as being important. Typically, people use this functionality to mark release points (v1.0, v2.0 and so on). In this section, you’ll learn how to list existing tags, how to create and delete tags, and what the different types of tags are.

```
git tag
```
**Listing the existing tags** in Git is straightforward. Just type git tag (with optional -l or --list). This command lists the tags in alphabetical order; the order in which they are displayed has no real importance.

---

```
git tag superRelease
```
Create a tag of a superRelease (we can move to any commit to create a tag).

---

```
git tag -a v1.0.0 -m "Version 1.0.0"
```
Create a tag in a more advanced way. We give it a name and a message.

---

```
git tag -a v0.1.0 345d7de -m "Version alfa"
```
Create a tag of an specific commit, the commit is 345d7de

---

```
git push --tag
```
Upload the tag to the repository.

---

```
git tag -d v1.4-lw
```
Delete the tag v1.4-lw *(Note that this does not remove the tag from any remote servers. There are two common variations for deleting a tag from a remote server.)*

---

```
git push origin :refs/tags/v1.4-lw
```
Delete the tag v1.4-lw from remote.

---

```
git push origin --delete <tagname>
```
Delete the tag tagname from remote.

---