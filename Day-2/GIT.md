# Git + GitHub

### What is Git?
Git is a distributed version-control system for tracking changes in source code during software development.
It is designed for coordinating work among programmers,
but it can be used to track changes in any set of files.
Its goals include speed, data integrity, and support for distributed, non-linear workflows.

### What is GitHub?

GitHub is a Git repository hosting service
Meaning GitHub is an online hosting service for development projects. It's also what you call a distributed version control system.

### What is the difference?
Simply put, Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories. If you have open-source projects that use Git, then GitHub is designed to help you better manage them.

## GIT Commands

### GIT Clone

Copy the repo url, you can find that in the repo.
Look for the green button named "Code" on the right.  

```
git clone [repo url]
cd [name of folder]
git remote origin
```
You can also verify the origins or URLs that git has stored

```
git remote -v
origin	https://github.com/freecodingbootcamp/Intro_to_GIT.git (fetch)
origin	https://github.com/freecodingbootcamp/Intro_to_GIT.git (push)
```

### Git Init

Start a new Git repository for an existing code base

```
cd /path/to/file
git init
git add .
git commit -m'write your note'
```
You can also verify if you're folder has git files by listing "all" the files and seeing the .git file

```
ls -a
.		..		.git		Git_Clone.md	Git_Init.md
```

### More commands...

## Other Notes

### Remote vs Local
Your local repository has the exact same features and functionality as any other repo.  This is great because there is no master or central repo you need to access to make certain changes or whatnot.  You are able to work out of your local repo in order to contribute to projects.   
Git local repository are the changes made on your local repository on your computer.

Git remote repository

### What is version control System?
 Say you're working on a huge project and have made multiple changes and broke the code but you're not sure where to backtrack to, or let's say you're working on a huge project with multiple people and you're all making changes. Well GitHub being a command line tool, you are constantly committing your changes and add messages each time you save and push to a remote repo. using these commands below:
 ```
 git add .
 git commit -m'I made my first change'
 git push origin
 ```




### Source

https://git-scm.com/docs/git-clone
https://git-scm.com/docs/git-init
https://en.wikipedia.org/wiki/Git
https://blog.devmountain.com/git-vs-github-whats-the-difference/#:~:text=GitHub%E2%80%A6-,what's%20the%20difference%3F,help%20you%20better%20manage%20them.
