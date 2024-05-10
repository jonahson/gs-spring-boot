## Hidden Folder

There is a hidden folder called `.git` which tells you that our project is a git repo.

If we wanted to create a git repo in a new project, we'll create the folder and then initialize that repo using `git init`

```
mkdir /workspaces/tmp/new-project
cd /workspaces/tmp/new-project
git init
touch Readme.md
code Readme.md
git status
# makes changes to Readme.md
git commit -a -m "add readme file"
```

## Cloning

We can clone three ways: HTTPS, SSH, Github CLI

Since we are using GitHub Codespaces, we'll creat ea temporary directory in our workspace

```sh
mkdir /workspace/tmp
cd /workspace/tmp
```

### HTTPS

```sh
git clone https://github.com/IISI-2303035/gs-spring-boot.git
```
git@github.com:IISI-2303035/gs-spring-boot.git
gh repo clone IISI-2303035/gs-spring-boot


## Commits

When we want to commit code, we can write git commit which will open up the commit edit message in the editor of choice.

```sh
git commit
```

set the globaleditor
```sh
git config --global core.editor emacs
```

## Branchs

## Remotes

## Stashing

## Merging

## Add

When we want to stage changes that will be included in that commit


```
git add Readme.md
git add.
```

## Reset

REset allows you to move Staged changes to be unstaged. This is useful when you want to revert all files not to be not commited.

```
git add .
git reset
```

## Status

Git status shows you what files will or will not be commited.

```
git status
```

## Gitconfig file

The gitconfig file is what stores your global configurations for git such as email, name, editor and more.

Showing the contents of our .gitconfig file
```
git config --list
```

