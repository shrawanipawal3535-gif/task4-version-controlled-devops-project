# Git Workflow Documentation

## 1. Repository Initialization

The Git repository was initialized using:

git init

## 2. Branches

The project uses three types of branches:

- main
- dev
- feature

## 3. Feature Development

Features are developed using feature branches.

Example:

feature/add-git-documentation

## 4. Pull Request

After completing a feature, a Pull Request is created:

feature -> dev

After testing:

dev -> main

## 5. Git Tag

Version v1.0.0 is created to mark the first release.

## 6. Git Stash

Git stash temporarily saves uncommitted changes.

## 7. Git Ignore

The .gitignore file prevents unwanted files such as logs, environment files and IDE folders from being committed.
