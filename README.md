# Course outline

This course is meant to be an introductory course to the world of `Git`. Primary audience are those who are either completely new to `Git`, never heard of it before,
or just want to expand their basic knowledge of `Git`.

## Language of instruction

This course is given in English.

## Programming language

To avoid confusion, `Git` is a version-control system (VCS), so it can be used with any programming language. Whether you are using `C++`, `Python`, `R`, `SAS` or
any other language of your preference, `Git` can help you to have control over your codebase.
We will demonstrate git on simple code in `Python` and `R`.

## Agenda

1. What is `Git`? Why do you want to (should) use it? Using `Git` for your personal projects and collaborative projects.
2. What is `GitHub` and (`Bitbucket`) and how they complement `Git`.
3. Cloning remote repository on your machine, remote vs. local - `git clone`
4. Explain difference between remote and local copy
5. Changing/checking git pull setting for cleaner history - `git config --global pull.rebase true`
6. Setting user name and email - `git config --global user.name/user.email`


### Together we will explore (Hands on section)

1. Creating own branches. Why branching and what is MAIN branch - `git checkout -b feature_branch`
2. Creating a new file and adding to staging index - `git status`, `git diff`, `git add`
3. Adding to commit history - `git commit`
4. Changing last commit message - `git commit --amend`
5. Pushing your changes to remote repository - `git push`
6. Reading the commit log - `git log`, `GitHub`
7. Get latest infomation and commits from remote - `git fetch`, `git pull`
8. Merging branches - `git merge`
9. Solving merge conflicts.
10. Solving pull requests.

### Lecturer will show (Observe section)

1. Merging branches part 2 - `git rebase`
2. How to revert a commit - `git revert SHA`
3. Unstaging files - `git reset` (soft, mixed, hard)
4. Taging the commits - `git tag -a <version> -m "<message>"`
5. Reverting unstaged changes - `git checkout`
6. .gitignore
