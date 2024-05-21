## `Hello everyone, welcome to learn Git & GitHub. This document only covers the essential things you need to know.`

### `Let's started`

# `1 - OVERVIEW & INSTALLATION | WHY WE NEED TO USE GIT AND GITHUB`

## `Difference Between Git & Github`

```
- Git is the tool, GitHub is the service for projects that use Git.
- Git is a revision control system, a tool to manage your source code history.
- GitHub is a hosting service for Git repositories.
```

### `Git`
```
- git is use to manage your own project locally
- making a check points 
- adding files 
- stagging them
- commiting them
- going back to some previous saved points 
- logging everything
- reverting back to the previous saved points
```

### `Github`

```
- github is a central code base where you host your git repositories. 
- to collabs with someone.
- to access your code everywhere you want.
```


## `Installatioin`

```
- install git for windows using the link below.
- [link](https://git-scm.com/download/win)
```

### `Git setup with vscode`

```
- git config --global user.name "name"
- git config --global user.email "email"
- git config --global core.editor "code --wait"
- git config --global core.autocrlf "input"
```

#

# `2 - BASICS`

### `Stages`

```
The staging area is a file, generally contained in your Git directory, that stores information about what will go into your next commit.
```

```
U - untracked
A - added
C - commited
M - modified
```


### `Commands you need to know`

```
- git ko enable karna | Initialization. => git init
- git per files wgera add kerna. => staging's | git add <filename to track>
- saved points create kerna. => git commit -m "commit message"
- uploads local commits to a remote repository. => git push
- kisi pechly saved point per wapis jana => git reset --hard HEAD~1
```
#

# `3 - STATUS | LOGS | BRANCHING & CONFLICTS`

###  `Status & logs`
```
- check kerny k liye konsi file kis stage me ha => git status -s 
- check kerny k liye k kitny saved points ha kitny commit ha => git log --oneline

- git status btata ha commit se pehly and bad apki files kis stage me ha
- git log sary commits ki history btata ha
```

### `Branching`

`What is branching`

```
- Branching allows you to create a separate copy of the project to work on, leaving the main project unchanged.
- This encapsulation makes it easy for multiple developers to work on a particular feature without disturbing the main codebase.
```
`Branching commands`

```
- to check how many branches has => git branch
- you create branches using this command => git checkout <branch name>
- you switch from one branch to another branch using this command => git switch <branch name>
- you can merge another branches code in the main branch using this command => git merge <branch name>
- to delete branch you can use thsi command => git branch -d <branch-name>
```

### `Conflicts`

`What is branching`

```
Conflicts in Git merging occur when changes in different branches overlap or contradict each other, making it unclear how to combine them. This typically happens when the same line of code is modified in different ways in two branches, or when a file is deleted in one branch but modified in another.
```

`Conflicts Options`

```
- accept current change => merge current branch code  
- accept incoming change => merge incoming branch code 
- accept both change => merge both branches code

Note: koi b change accept kerny k bad add ker k commit kerna pary ga
```

# `4 - COLLABORATION`

### `Common Steps to collabs with friend's`

```
- team lead project ka folder bnaye ga initial code likhy ga or repo bna k us code ko github per push ker dega
- jo log teammate hain unko collaborators add kary ga
- har banda us repo se cloning kary or apni apni branch create kary or apna code usme kary
- apna task hony per commit ker k github push kerdein or lead ko btadein code push ker dia ha
- team lead git fetch kary ga code review ker k merge kary ga and commit ker k repush kerdy ga
- us k bad jab b baqi members kam start kerny lgy gy git pull kary ge un k pas github se updated code ajaye ga
```

#
# `5 - 5 STEPS TO START NEW PROJECT WITH GITHUB`

```
- Create a "repository" (project)
- Copy (or clone) the repository to your local machine.
- Add a file to your local repo and "commit" (save) the changes.
- "Push" your changes to your main branch.
- Make a change to your file and commit.
```



# 
#
Git and Github by [Hafiz Abdullah](https://hafizabdullah.site)😊
