# Git Cheat Sheet

## Change the active user for Git.

When you are starting work in a new repo you'll want to set the user for the commits you will make

```
$ cd into/the/folder/you/are/working/in
$ git config user.name "yourusername"
$ git config user.email your@email.com

## Standard branching and pull request workflow

Standard git project workflow

Given that you have cloned a repo, the standard process for adding code to the repo is as follows:

1) cd into your cloned repository
2) create a branch to work in
3) code
4) stage changes
5) commit changes
6) push the branch up to Github
7) make a pull request

This workflow roughly translates to these steps/commands:

1) cd your-repository
2) git checkout -b add_my_new_feature
3) write some code
4) git add .
5) git commit -m 'add my new feature'
6) git push origin add_my_new_feature
7) on the repo page click Compare and Pull Request on the branch, or select your branch from the dropdown and Create Pull Request from that page
```
