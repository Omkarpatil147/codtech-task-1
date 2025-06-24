# CODTECH-TASK-1  
# VERSION CONTROL WITH GIT  

**COMPANY**: CODTECH IT SOLUTIONS  
**NAME**: OMKAR RAJENDRA PATIL  
**INTERN ID**: CT08DM1418  
**DOMAIN**: DevOps  
**DURATION**: 8 WEEKS  
**MENTOR**: NEELA SANTOSH KUMAR  

---

## DESCRIPTION OF TASK

The aim of this task was to understand and implement Git version control with a focus on branching, merging, and resolving conflicts. As a DevOps intern, mastering Git is critical because it is the backbone of source control in collaborative development environments. In this task, I created a GitHub repository and cloned it to my local system. I then created a file named `file.txt` and committed it to the `main` branch. 

After that, I created two new branches: `feature-A` and `feature-B`. Both branches were created from the `main` branch and modified the same file in different ways. This setup was intentionally designed to produce a merge conflict when both were merged back into the `main` branch.

First, I merged `feature-A` into `main` without any issues. Then, I attempted to merge `feature-B` into `main`, which resulted in a conflict in `file.txt` because both branches had edited the same section of the file. Git clearly marked the conflicting areas in the file with `<<<<<<<`, `=======`, and `>>>>>>>` markers.

To resolve the conflict, I manually edited the file to include both changes in a meaningful way, removed the conflict markers, saved the file, and added it to staging. I committed the resolution with a clear message, indicating that the conflict had been resolved.

Finally, I pushed all three branches (`main`, `feature-A`, and `feature-B`) to GitHub, ensuring that the complete commit history and branch structure were visible. This task helped me get hands-on experience with Git operations that are essential in real-world DevOps and software engineering workflows.

Through this task, I learned not only how to perform basic Git operations but also how to identify and resolve merge conflicts. This skill is invaluable in team environments where multiple developers might work on the same codebase. The practice also reinforced the importance of meaningful commit messages and maintaining a clear project history for better collaboration and troubleshooting.

---

## OUTPUT

### 🔹 GitHub Repository:
[https://github.com/Omkarpatil147/codtech-task-1](https://github.com/Omkarpatil147/codtech-task-1)

### 🔹 Branches:
- `main`
- `feature-A`
- `feature-B`

### 🔹 Files:
- `file.txt` (contains combined changes)
- `README.md` (you are reading it)

### 🔹 Git Actions Performed:
- `git init`
- `git checkout -b`
- `git merge`
- Merge conflict resolution
- `git push origin branch-name`


