Day 09 - Git Branching
Date: 18-02-2026
Objective:
To understand Git branching and merging concepts for collaborative development.
Introduction:
Branching in Git allows developers to work on new features or bug fixes without affecting the main project code.
By default, Git creates a branch called "main" (or master in older versions).

 Why Branching is Important:
- Allows parallel development
- Prevents unstable code in main branch
- Makes collaboration easier
- Supports feature-based development

Git Branch Commands Practiced:
git branch  
Lists all branches
git branch branch\_name  
Creates a new branch
git checkout branch\_name  
Switches to a branch
git checkout -b branch\_name  
Creates and switches to a new branch
git merge branch\_name  
Merges a branch into current branch
git branch -d branch\_name  
Deletes a branch

Practical Activity:
- Created a new branch for feature development
- Modified a file
- Committed changes
- Merged branch into main

Merge Conflicts:

A merge conflict occurs when two branches modify the same part of a file.
Conflicts must be resolved manually before completing the merge.
Importance in DevOps:

- Used in CI/CD pipelines

- Supports multiple developers

- Enables safe feature development

Conclusion:
Today I learned about Git branching, merging, and handling merge conflicts in collaborative development environments.

