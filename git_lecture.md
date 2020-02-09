## Git configuration

```

git config --global user.email "me@example.com"

git config --global user.name "My name"

git config user.name

git config user.email

```

## Create a git Repository


1. **git init**  --create a git repo from scratch

1. **git clone** --make a copy of git repo that exist somewhere else

```

mkdir testdir
cd testdir
git init
ls -al
ls -l .git\
```

**.git directory** --stores the changes and change history

---------

## Quiz

#### What are the git directory and the working tree?

```
[ ] The git directory stores configuration settings and the working tree stores the history of the files.

[ ] The git directory is copied to the computer and the working tree stays in the remote repository.

[ ] The git directory is a sandbox for changing the files and the working tree contains old versions of the files.

[ ] The git directory contains all the changes and their history and the working tree contains the current versions of the files.

```

```bash

touch README.md
echo "# Insert the name of the project" >> "README.md"

git add README.md

git status

git commit -m "initial commit"
```

### Staging area
A file maintained by gitt hat contains all the information about what files and changes are going to go into next commit

## Quiz

##### What do we need to do after modifying a file tracked by Git?

>>>
- [ ] We need to stage the file, so that the changes will be included in the next commit.


- [ ] We need to commit the file, so that the changes will become part of the staging area.

- [ ] We need to add the file to the Git directory.

- [ ] We need to change to a different working tree.

--------

### Practice Quiz: Using Git


1. Before changes in new files can be added to the Git directory, what command will tell Git to track our file in the list of changes to be committed?


- [ ] git status


- [ ] git add


- [ ] git commit


- [ ] git init

----------

2.Which command would we use to review the commit history for our project?


- [ ] git clone


- [ ] git status


- [ ] git config -l


- [ ] git log
-------

## Lab

#### What you'll do

- Create a git repository.
- Add files to this repository
- Edit the files
- Commit the changes to the repository.


