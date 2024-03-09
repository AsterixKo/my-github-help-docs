### GIT ALIASES
Git doesn’t automatically infer your command if you type it in partially. If you don’t want to type the entire text of each of the Git commands, you can easily set up an alias for each command using git config. Here are a couple of examples you may want to set up:

```
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.st status
```
This commands adds the alias co, br, ci, st.

---

```
git config --global alias.lg "log --oneline --decorate --all --graph"
```
This command add the alias lg for view the commits log

---

```
git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"
```
This command adds the alias lg for view the commits log on a better way.

---

```
git config --global alias.s "status -s -b"
```
This command adds the alias s for view the status on a simple way.

---

```
git config --global -e
```
Opens the global configuration in the editor.

---