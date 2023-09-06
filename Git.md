### Basic GIT Commands

- `git init` // initializes a new Git repository in the current directory
- `git status` // shows the current status of the repository
- `git add` // adds a specific file to the staging area
- `git add .` // adds all new and changed files to the staging area
- `git reset <file>` // removes the specified file from the staging area but retains the changes
- `git commit -m “My Message”` // commits the staged changes with a message
- `git commit -a -m "message"` // stages all tracked, modified files and commits them with a message in one step
- `git log —oneline` // shows the commit history in a single line format
- `git commit --amend` // amends the most recent commit
- `git branch` // lists all branches in the repository
- `git branch <branch-name>` // creates a new branch with the given name
- `git switch <branch-name>` // switches to the specified branch
- `git switch -c <branch-name>` // creates a new branch and switches to it
- `git checkout <branch-name>` // switches to the specified branch
- `git branch -d <branch-name>` // deletes the specified branch safely, only if it has been fully merged in its upstream branch
- `git branch -D <branch-name>` // deletes the specified branch forcefully, regardless of its merge status
- `git branch -m <old-name> <new-name>` // renames the branch from `<old-name>` to `<new-name>`
- `git branch -m <new-name>` // renames the current branch to `<new-name>`
- `git merge <branch-name>` // merges the specified branch into the current branch

- `.gitignore` // a text file where you can specify files and folders that git should ignore