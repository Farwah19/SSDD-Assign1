# SSDD Assignment 1 – Git & GitHub 

## 🔹 Step 1 – Repository Setup  

- Created a repository named **`SSDD-Assign1`** on GitHub.  
- Cloned the repository locally.  
- Added `first.txt`, staged, committed, and pushed it to GitHub.  

---

## 🔹 Step 2 – Collaborating with Branches  

- Created a new branch: **`feature/additional-feature`**.  
- Added `newFile.txt`, committed, and pushed the branch.  
- Opened a Pull Request (PR) and invited a collaborator to review it.  
- After approval, merged the PR into `main`.  

---

## 🔹 Step 3 – Forking & PR to Original Repo  

- Forked a teammate’s public repository.  
- Cloned the fork locally and made edits.  
- Committed and pushed changes to my fork.  
- Opened a PR to the original repository.  

---

## 🔹 Step 4 – Revert & Reset  

- Created a new file and committed changes.  
- Used `git revert <hash>` to undo the commit (safe history-preserving undo).  
- Made another commit and then used `git reset --hard <hash>` to move back to a previous commit (history rewritten).  

---

## 🔹 Step 5 – Collaboration Workflow with Conflicts  

- Created a branch `conflict-branch`.  
- Edited `demo.txt` differently in both `main` and `conflict-branch`.  
- Merged branches → Git raised a conflict.  
- Resolved the conflict manually, staged, committed, and completed the merge.  

---
