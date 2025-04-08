# Git Basic Guide
*by Hanna Milnikel*
**Date:** 08.04.2025

## About This Project
This repository contains summary of basic git commands.

## Configuration
in terminal (bash)

### Set your global username
`git config --global user.name "Your Name"`

### Set your global email
`git config --global user.email "your.email@example.com"`

### Set your preferred text editor (I use Sublime Text)
`git config --global core.editor "subl -n -w"`

## Repository

### Clone a repository
`git clone git@github.com:username/repository.git`

### Initialize a new repository
`git init`

## Making Changes

- `git add "filename.py"` -  stage a file for commit
- `git commit -m "message"` – commit changes with a message
- `git push origin main` – send changes to GitHub
- `git pull origin main` – pull changes from GitHub

### Example changes in README.md file:

1. Open the `README.md` file for editing:
```bash
subl README.md 
```
2. Edit the file in your text editor
3. Upload changes from your local machine to your online repository
```bash
git add README.md
git commit -m "readme"
git push origin main
```