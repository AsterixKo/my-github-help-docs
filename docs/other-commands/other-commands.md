### OTHER COMMANDS
Other commands.

Go to commit a1b2c3:
```
git checkout a1b2c3
```
... and return to main with:
```
git checkout main
```
Go back to a specific commit then go back to the present

---

```
git add .
```
Stage all files (that are not listed in the .gitignore) in the entire repository.

---

```
git add -A
```
Stages all files, including new, modified, and deleted files, including files in the current directory and in higher directories that still belong to the same git repository

---

```
git add -u
```
Stages modified and deleted files only, NOT new files

---

```
git add *.png
```
Stages all png files.

---

```
git add <path>
```
Stage a specific directory or file

---

```
git add directory/
```
Stage all changes to all files within a directory titled directory.

---

```
git add README.md
```
Stage all changes within the README.md file.

---


**Using git reset to undo git add**

`git reset` is a flexible and powerful command. One of its many use cases is to move changes out of the staging area. To do this, use the "mixed" level of reset, which is the default.

To move staged changes from the staging area to the working directory without affecting committed history, first make sure that you don't have any additional changes to the files in question as mentioned above. Then, type `git reset HEAD` (aka `git reset --mixed HEAD`).
```
git reset HEAD
```
To move staged changes from the staging area to the working directory without affecting committed history...

---

**Unstage**

```
git reset HEAD <file>
```
To remove files from staging, but keep your changes

---

```
git reset HEAD^3
```
To unstage the last three commits

---

```
git reset <filename>
```
To unstage changes to a certain file from HEAD

---

```
git checkout -- <file>
```
After you unstage the file, to revert the file back to the state it was in before the changes

---

**Remove a file**

```
git rm '*.txt'
git rm -r <dirname>
```
To remove a file from disk and repository, use `git rm`. To remove a directory, use the `-r` flag

---

```
git rm <filename> --cache
```
To keep a file on disk but remove it from the repository (such as a file you want to add to `.gitignore`), use the `rm` command with the `--cache` flag

---