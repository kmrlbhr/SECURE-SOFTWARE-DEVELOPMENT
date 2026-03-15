# Complex Calculator in C

A menu-driven calculator program written in **C** that supports both basic and advanced mathematical operations.  
This project is designed as a learning example for students to practice programming and GitHub workflows.

---

## ✨ Features
- Addition, subtraction, multiplication, division
- Power function (exponentiation)
- Square root calculation
- Factorial of integers
- Error handling (division by zero, negative inputs for square root/factorial)

---
## Common GitHub Commands for Students
===================================
https://git-scm.com/install
This guide explains the most useful GitHub commands with examples using the Complex-Calculator-C project.

------------------------------------------------------------
1. Initialize a new repository
------------------------------------------------------------
Command:
    git init
    
Explanation:
    Creates a new Git repository in the current folder.
    
Example:
    cd Complex-Calculator-C
    git init

------------------------------------------------------------
2. Clone an existing repository
------------------------------------------------------------
Command:
    git clone <repository-url>
    
Explanation:
    Copies a repository from GitHub to your computer.
    
Example:
    git clone https://github.com/BakhtiarIman95/GithubCommandExercise_Calculator.git

------------------------------------------------------------
3. Check repository status
------------------------------------------------------------
Command:
    git status
    
Explanation:
    Shows which files have been modified, staged, or untracked.
    
Example:
    git status

------------------------------------------------------------
4. Stage changes
------------------------------------------------------------
Command:
    git add <filename>
    git add .
    
Explanation:
    Prepares files to be committed. "git add ." stages all files.
    
Example:
    git add calculator.c
    git add README.md

------------------------------------------------------------
5. Commit changes
------------------------------------------------------------
Command:
    git commit -m "Your commit message"
    
Explanation:
    Saves staged changes into the repository history.
    
Example:
    git commit -m "Added factorial function to calculator"

------------------------------------------------------------
6. Push changes to GitHub
------------------------------------------------------------
Command:
    git push origin main
    
Explanation:
    Uploads local commits to the GitHub repository.
    
Example:
    git push origin main

------------------------------------------------------------
7. Pull latest changes from GitHub
------------------------------------------------------------
Command:
    git pull origin main
    
Explanation:
    Downloads and merges changes from GitHub into your local repo.
    
Example:
    git pull origin main

------------------------------------------------------------
8. Create a new branch
------------------------------------------------------------
Command:
    git branch <branch-name>
    
Explanation:
    Creates a new branch for separate development.
    
Example:
    git branch feature-logarithm

------------------------------------------------------------
9. Switch to another branch
------------------------------------------------------------
Command:
    git checkout <branch-name>
    
Explanation:
    Moves you to the branch you specify.
    
Example:
    git checkout feature-logarithm

------------------------------------------------------------
10. Merge a branch into main
------------------------------------------------------------
Command:
    git checkout main
    git merge <branch-name>
    
Explanation:
    Combines changes from another branch into main.
    
Example:
    git checkout main
    git merge feature-logarithm

------------------------------------------------------------
11. View commit history
------------------------------------------------------------
Command:
    git log
    
Explanation:
    Shows a list of past commits with details.
    
Example:
    git log

------------------------------------------------------------
12. Undo changes (reset file to last commit)
------------------------------------------------------------
Command:
    git checkout -- <filename>
    
Explanation:
    Restores a file to its last committed state.
    
Example:
    git checkout -- calculator.c

------------------------------------------------------------
13. Remove a file from staging
------------------------------------------------------------
Command:
    git reset <filename>
    
Explanation:
    Unstages a file that was added with git add.
    
Example:
    git reset README.md

------------------------------------------------------------
14. Delete a branch
------------------------------------------------------------
Command:
    git branch -d <branch-name>
    
Explanation:
    Deletes a branch locally.
    
Example:
    git branch -d feature-logarithm

------------------------------------------------------------
Practice Workflow for Students
------------------------------------------------------------
1. Clone the repo:
    git clone https://github.com/BakhtiarIman95/GithubCommandExercise_Calculator.git

2. Make a change (e.g., add a new math function in calculator.c).

3. Stage and commit:
    git add calculator.c
    git commit -m "Added logarithm function"

4. Push to GitHub:
    git push origin main

5. Create a branch:
    git branch feature-trigonometry
    git checkout feature-trigonometry

6. Merge branch back into main:
    git checkout main
    git merge feature-trigonometry
