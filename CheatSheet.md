# Git basic architecture

## Able to better understand git; we should know some key terminologies

- **Repository**
  - A git repository is a collection of files that we have in the projects where to store under the .git folder
- **Working Directory**
  - Wd is a folder where your documents and .git folder located
- **Commit**
  - When you commit your changes you are taking a snapshot of your project and store it permanently in your repository.
- **Staging(Index)**
  - The git kept monitoring all changes we have done in the staging area. Keeping files in your staging area will give you a chance to review your changes before saving(committing) to your repository.
- **Please don't forget**; The git does not store deltas or what was changed. The git store all the content in a very efficient way. Storing all projects will give us the option to restore them very quickly at any previous time the projects.

![Git workflow](/git-workflow.png)

## Let's get started with git basic commands

|Command| Example  |  Description |
|:---|:---|:---|
|config | git config --global user.name "username" | You need to configure your username and email. The configuration can be done globally or only for specific reporsitory|
|config | - git config --global user.email "youremail@yourdomain.com" ||
|init   | git init  | Initalize a new git repository in the current folder. It creates a .git folder which is hidden by default. **Please do not touch or change manually in this folder.** |
| Add files to the repository  | git add file1.txt file2.txt or git add .  | You can specify the file name(s) or just "." that you want to add in the staging area. If you use the git add. it will recursively add all files in the repository, but you may not want to add all files in your repository therefore you need to create a special file to ignore them. **Git is not automatically tracked the file added to the directory. You should explicitly tell the git to keep track of them** |
| Status  | git status  | Show the current repository status  |
| Log  |  git log or git log --grep="Keyword" or git log -n 5 |  Show logs in the current branch|
| Commit  | git commit -m "message"  | The current snapshot will be written permanently in the repository. **Commit message is also important for a later stage to understand what is changed.**|
| Differences |  git diff "old commit Id" "new commit Id" | You can see the differences between commits. |
| Show  | git show "commit Id"  | Shows us all changes that were made in this commit. |
| Branch  | git branch  | Shows a list of branches in the repository  |
| Branch  | git branch -r | Shows a list of branches from remote stream if you have it.|
| - New   |  git branch "branch_name" | Creates a new branch named "branch_name" |
| - Checkout | git branch -b  "branch_name"  | Swichtes between your branches  |
|  - Delete | git branch -d "branch_name"    | Delete branche.  |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
