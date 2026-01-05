# Introduction to Git and Targets

-----

:busts_in_silhouette: Robert Ladwig  
:email: [Questions?](mailto:rladwig@ecos.au.dk)

-----

## Aim of this introduction

The aim is to introduce hands-on coding on how to use Git for data management and joint coding, as well as the targets R-package for reproducible data pipelines.

## What is Git?

Git is a software which is used to keep track of files that are being simultaneously edited by multiple users (and allows you to publish them all). GitHub (owned by Microsoft), on the other hand, is a Git server. It's a remote location where you can host code that is stored in Git.

## What is Targets?

Targets is an R-package, which allows you to build Make-like pipelines (so you can create reproducible workflows) for statistics and data science. The package skips costly runtime for tasks that are already up to date, orchestrates the necessary computation with implicit parallel computing, and abstracts files as R objects (more efficiency).

Targets has a minimum structure of
```
├── _targets.R
├── R/
│   ├── functions.R
```

## Important Git vocabulary

- repositories
- branches
- fork
- clone
- push and pull
- pull request

## Important Git commands

```
git clone
git status
git pull 
git add .
git commit -m "MESSAGE"
git push
```

## Important Targets commands

```
tar_make()
tar_read()
```

## Why use Git and Targets?

You can work collaboratively on your code (which will make it better eventually), track changes and easily publish all data (for reproducibility and to have a backup). Further, you can run the whole workflow again later without needing to remember all details. 

## Next? Do the [GitHub](https://github.com/skills/introduction-to-github) and [Targets](https://books.ropensci.org/targets/walkthrough.html) tutorials

