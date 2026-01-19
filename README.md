# Git & GitHub Assignments – Practical Repository

This repository contains **five Git & GitHub practical assignments**, completed as part of academic lab work. Each assignment demonstrates real-world Git workflows using command-line Git and GitHub.

---

## Assignment 1: Basic Git Operations

### Objective

To understand basic Git operations such as initializing a repository, committing changes, cloning, fetching, and pulling from a remote repository.

### Steps Performed

1. Created a new local Git repository using `git init`.
2. Created a file and committed it to the repository.
3. Viewed commit history using `git log`.
4. Modified the file and verified its status using `git status`.
5. Staged and committed the modified file.
6. Created a GitHub repository and pushed local commits.
7. Cloned the GitHub repository.
8. Fetched updates using `git fetch`.
9. Pulled changes using `git pull`.

### Key Commands Used

```bash
git init
git status
git add .
git commit -m "message"
git log
git clone <repo-url>
git fetch
git pull
```

---

## Assignment 2: Branching and Merging

### Objective

To understand branching, switching branches, merging changes, and pushing merged code to GitHub.

### Steps Performed

1. Cloned the repository from GitHub.
2. Created a new branch.
3. Switched to the new branch.
4. Modified files and committed changes in the feature branch.
5. Switched back to the main branch.
6. Merged the feature branch into the main branch.
7. Pushed merged changes to GitHub.

### Key Commands Used

```bash
git branch <branch-name>
git checkout <branch-name>
git merge <branch-name>
git push origin main
```

---

## Assignment 3: Pull Request and Conflict Resolution (Using Rebase)

### Objective

To create a pull request, intentionally create a conflict, and resolve it using `git rebase`.

### Steps Performed

1. Created a feature branch and pushed changes to GitHub.
2. Created a Pull Request.
3. Made conflicting changes to the same file in the main branch.
4. Observed merge conflict in the Pull Request.
5. Resolved the conflict using `git rebase`.
6. Force-pushed the rebased branch.
7. Successfully merged the Pull Request.

### Conflict Resolution Commands

```bash
git fetch
git rebase origin/main
git add <file>
git rebase --continue
git push origin <branch-name> --force
```

### Explanation

A conflict occurred because the same file was modified in both branches. The conflict was resolved by rebasing the feature branch onto the updated main branch and manually resolving the conflicting changes.

---

## Assignment 4: Cherry-Pick

### Objective

To selectively apply specific commits from one branch to another using `git cherry-pick`.

### Steps Performed

1. Created a feature branch.
2. Made multiple commits by modifying the same file multiple times.
3. Identified specific commit hashes using `git log --oneline`.
4. Switched to the main branch.
5. Cherry-picked selected commits from the feature branch.
6. Pushed the changes to GitHub.

### Key Commands Used

```bash
git log --oneline
git cherry-pick <commit-hash>
git push origin main
```

### Explanation

Cherry-pick allows applying only required commits instead of merging the entire branch.

---

## Assignment 5: Git Concepts Demonstration

### Objective

To demonstrate understanding of advanced Git concepts used throughout the assignments.

### Concepts Covered

* Git Fetch vs Git Pull
* Branching Strategy
* Merge vs Rebase
* Conflict Resolution
* Cherry-Pick

### Summary

This assignment consolidates practical understanding of Git workflows commonly used in collaborative software development.

---

## Tools Used

* Git (Command Line)
* GitHub
* Git Bash (Windows)

---

## Conclusion

These assignments provided hands-on experience with Git and GitHub, including version control basics, collaboration workflows, conflict resolution, and selective commit management. The repository demonstrates practical Git usage aligned with real-world development practices.

---

