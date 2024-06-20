# start a working area (see also: git help tutorial)

## clone

- Clone a repository into a new directory

```sh
git clone <repository>
```

## init

- Create an empty Git repository or reinitialize an existing one

```sh
git init
```

# work on the current change (see also: git help everyday)

## add

- Add file contents to the index

```sh
git add <file>
```

## mv

- Move or rename a file, a directory, or a symlink

```sh
git mv <oldpath> <newpath>
```

## restore

- Restore working tree files

```sh
git restore <file>
```

## rm

- Remove files from the working tree and from the index

```sh
git rm <file>
```

# examine the history and state (see also: git help revisions)

## bisect

- Use binary search to find the commit that introduced a bug

```sh
git bisect start
```

## diff

- Show changes between commits, commit and working tree, etc

```sh
git diff
```

## grep

- Print lines matching a pattern

```sh
git grep <pattern>
```

## log

- Show commit logs

```sh
git log
```

## show

- Show various types of objects

```sh
git show <object>
```

## status

- Show the working tree status

```sh
git status
```

# grow, mark and tweak your common history

## branch

- List, create, or delete branches

```sh
git branch
```

## commit

- Record changes to the repository

```sh
git commit -m "<message>"
```

## merge

- Join two or more development histories together

```sh
git merge <branch>
```

## rebase

- Reapply commits on top of another base tip

```sh
git rebase <branch>
```

## reset

- Reset current HEAD to the specified state

```sh
git reset <commit>
```

## switch

- Switch branches

```sh
git switch <branch>
```

## tag

- Create, list, delete or verify a tag object signed with GPG

```sh
git tag <tagname>
```

# collaborate (see also: git help workflows)

## fetch

- Download objects and refs from another repository

```sh
git fetch
```

## pull

- Fetch from and integrate with another repository or a local branch

```sh
git pull
```

## push

- Update remote refs along with associated objects

```sh
git push
```
