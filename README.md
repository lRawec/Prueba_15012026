# Prueba_15012026
Repositorio de Prueba para la clase de Diseño de Aplicaciones Web. 

## Homework 1 Application Web Design
> Editing a README file, listing commands used in Git:

#### Check the Status
To see which files are staged, unstaged or untracked we can use the command:
+ `git status`

#### Add Files
Before commiting, we have to tell Git which changes we want to include.
We can add individual files with `git add <filename>` or we can add global/all changes with `git add .`

#### Add comments to a Commit
A commit is a snapshot of the project so the comment must explain what changes we made.
The standard commit:
- `git commit -m "message here"`

#### Upload Changes to Remote
To send our local commits to the server, we can make a standar push with `git push origin <branch_name>` or with `git push -u origin <branch_name`

#### Create, Browse and Delete branches
Branches allows us to work on new features without breaking the main code.
+ **Create a Branch:** `git branch <branch_name>`
+ **Switch to a Branch:** `git checkout <branch_name>` or `git switch <branch_name>`
+ **Browse/List Branches:** `git branch`
+ **Delete a Branch:** `git branch -d <branch_name>` 

#### Roll Back to a Specific Commit
This is a nice aspect of Git because let us "time travel" to a specific commit.
There are some options to do this:
+ `git reset --soft <commit_id>` (This will Undo the changes but will keep the code).
+ `git reset --hard <commit_id>` (This will wipe everything back to that point).
+ `git revert <commit_id>` (This will create a new commit that undoes a previous one).

> Tip. We can find the <commit_id> by running `git log --oneline` that will shows a long list of strings of numbers and letters.