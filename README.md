# Git Custom Commands

## Download
Download these files into your PATH (/usr/local/bin/, for example)

## Permissions
Make the files executable, readable and writeble (chmod 777 on linux, for example)

## Run the command
Now you can run the new git custom command in your repository! Just type 'git command_name' with the parameters if needed

> For more info about git custom commands, see https://github.com/rotati/wiki/wiki/Create-custom-Git-command



# Commands in this repository

## git-create-branch
It creates a new branch from the current branch or from the branch passed as parameter

**Usage:** 
* `git create-branch {new_branch_name}` to create a new branch from your current one;
* `git create-branch {new_branch_name} {source_branch_name}` to specific the source branch

## git-fork-branch
It pushes a new branch from the forked repo into yours.

**Usage:** `git fork-branch {branch_name}`

## git-update
It syncs your repo's branch with the original one, in the forked repository.

**Usage:** `git update {branch_name}`
