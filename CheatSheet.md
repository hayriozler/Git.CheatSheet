# Git basic architecture

## Able to better understand git; we should know some key terminologies

- **Repository**
  - A git repository is a collection of files that we have in the projects where to store under the .git folder
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
| Add files to the repository  | git add file1.txt file2.txt or git add .  | You can specify a file that you want to add in the staging area. |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
