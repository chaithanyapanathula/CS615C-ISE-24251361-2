# CS615C-ISE-24251361
Name : Panathula chaithanya siva sai venkatesh



# Git Workflow Guide

## 1. Clone a Repository
```sh
git clone <repository-url>
```
Clones an existing repository to your local machine.

## 2. Navigate to the Project Directory
```sh
cd <repository-name>
```
Changes the directory to the cloned repository.

## 3. Create a New Branch (Optional)
```sh
git checkout -b <branch-name>
```
Creates and switches to a new branch.

## 4. Make Changes & Stage Files
```sh
git add <file-name>  # Add a specific file
git add .  # Add all changes
```
Stages the modified files for commit.

## 5. Commit Changes
```sh
git commit -m "Your commit message"
```
Saves the changes with a descriptive message.

## 6. Push Changes to Remote Repository
```sh
git push origin <branch-name>
```
Uploads local changes to the remote repository.

## 7. Pull Latest Changes (If Collaborating)
```sh
git pull origin <branch-name>
```
Fetches and merges the latest changes from the remote branch.

## 8. Merge Branch to Main (After Review)
```sh
git checkout main
git merge <branch-name>
git push origin main
```
Merges the branch into the main branch and updates the remote repository.

## 9. Delete a Branch (Optional)
```sh
git branch -d <branch-name>
```
Deletes the branch locally after merging.

---

