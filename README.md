# SCM Basics – Project: Git

This repository contains my introductory work with Git as part of the Holberton School curriculum.  
It focuses on understanding version control, working with repositories, and collaborating using Git and GitHub.

## Table of Contents
- [Description](#description)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [Repository Structure](#repository-structure)
- [Tasks Overview](#tasks-overview)
- [Author](#author)

## Description
This project introduces the fundamentals of **Git** and **GitHub**, including local and remote repository management, branching strategies, merge workflow, and rollback techniques. The project is hands-on and follows real-world development practices.

## Learning Objectives
By completing this project, I learned how to:
- Initialize and configure Git on a local machine
- Work with local repositories (`git add`, `commit`, `status`, `log`)
- Configure user identity and `.gitignore`
- Connect to a remote repository on GitHub (`origin`)
- Push and pull with authentication via Personal Access Token
- Create and manage branches
- Merge branches and resolve conflicts
- Roll back changes with `git reset` and `git revert`
- Follow a complete GitHub workflow with Pull Requests

## Requirements
- OS: Ubuntu or Linux environment
- Git installed (`git --version`)
- GitHub account configured with a Personal Access Token
- Each step validated using `git status`, `git log`, and GitHub interface
- Clear commit messages recommended
- Project follows Holberton checker rules and validation

## Repository Structure
```
git-intro/
├── README.md
├── .gitignore
├── greeting.txt
├── message.txt
└── (other files created during the tasks)
```

## Tasks Overview
| Task | Topic | Key Commands Used |
|------|-------|-------------------|
| 0 | Initial setup | `git init`, `git config`, `git remote` |
| 1 | First commits | `git add`, `git commit`, `.gitignore` |
| 2 | Push & pull | `git push`, `git pull`, token authentication |
| 3 | Branch creation | `git branch`, `git checkout -b` |
| 4 | Merge & conflicts | `git merge`, conflict resolution |
| 5 | Rollback | `git reset`, `git revert`, tags |
| 6 | Complete workflow | GitHub PR, merge, conflict, rollback |

Each step builds on the previous one to reproduce a professional Git workflow.

---

## Author
**Félix Besançon**  
Software Engineering Student @ Holberton School  
📧 f.besancon@hotmail.fr  
🔗 https://github.com/FelixBesancon
