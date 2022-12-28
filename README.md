# Git Docs

View on [Notion](https://haxrox.notion.site/Git-Docs-4b940d8c94434adbb196abf2ccf8b9ff)

<aside>
Git is a version control system that allows developers to collaborate on projects and keep track of changes. GitHub is a hosting platform for version control and collaboration on projects.

</aside>

# Git Commands Docs

[Reference](https://git-scm.com/docs)

# GitHub Docs

[GitHub.com Help Documentation](https://docs.github.com/en)

# Cheat Sheet

[github-git-cheat-sheet.pdf](github-git-cheat-sheet.pdf)

[GitHub Git Cheat Sheet](https://training.github.com/downloads/github-git-cheat-sheet/)

# Training

[GitHub Training Kit](https://training.github.com/)

# Licensing

[Choose an open source license](https://choosealicense.com/)

# Using Git/GitHub

## Repository Creation

### New Repository

```bash
echo "<Text>" >> README.md # create your first file in the repo
git init
git add README.md
git commit -m "<commit message>"
git branch -M main
git remote add origin <repo_url>
git push -u origin main
```

### Existing Repository

```bash
git remote add origin >repo_url>
git branch -M main
git push -u origin main
```

## Git Commands

Git has many commands available to help you manage your projects. Some of the most common commands are:

- `git init`: Creates an empty Git repository in the current folder
- `git clone <url>`: Clones a remote repository to your computer
- `git add <file>`: Adds a file to the staging area
- `git commit -m "<message>"`: Commits the changes to the repository with a message
- `git push`: Pushes the changes to a remote repository
- `git pull`: Pulls changes from a remote repository

### Branches

Branches are used to work on different versions of a project simultaneously. You can create, delete, and merge branches as needed. Common branch commands include:

- `git branch <name>`: Creates a new branch with the given name
- `git checkout <name>`: Switches to the branch with the given name
- `git merge <name>`: Merges the branch with the given name into the current branch
- `git branch -d <name>`: Deletes the branch with the given name

### Submodules

Submodules allow you to include other Git repositories inside your own repository. This is useful for managing dependencies and keeping track of external changes.

- `git submodule add <url>`: Adds a submodule from the given url
- `git submodule init`: Initializes the submodules
- `git submodule update`: Updates the submodules to their latest version
- `git submodule status`: Shows the status of the submodules