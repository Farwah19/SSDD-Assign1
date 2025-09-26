# SSDD Assignment 1 – Git & GitHub  

## 🔹 Step 1 – Repository Setup  

- I created a new repository on GitHub and named it **`SSDD-Assign1`**.  
- Then I cloned the repo to my local machine.  
- Inside it, I added a file called `first.txt`, wrote some text, staged it, committed it, and pushed it back to GitHub.  

---

## 🔹 Step 2 – Collaborating with Branches  

- I made a new branch called **`feature/additional-feature`**.  
- In that branch, I added a file `newFile.txt`, committed the changes, and pushed it.  
- After that, I opened a Pull Request (PR) and asked my teammate to review it.  
- Once it was approved, I merged it into the main branch.  

---

## 🔹 Step 3 – Forking & PR to Original Repo  

- I went to my teammate’s GitHub repo and forked it into my own account.  
- After cloning the fork locally, I made some edits in one of the files.  
- Then I committed and pushed the changes to my fork.  
- Finally, I opened a PR to the original repo so my changes could be added there.  

---

## 🔹 Step 4 – Revert & Reset  

- I tested **revert** by creating a new commit and then running `git revert <hash>`. This made a new commit that undid my changes.  
- I also tested **reset** by making another commit and then running `git reset --hard <hash>`. This moved the branch back to that commit, deleting the ones after it.  

---

## 🔹 Step 5 – Collaboration Workflow with Conflicts  

- To practice conflicts, I created a branch called `conflict-branch`.  
- On that branch, I edited the file `demo.txt` and committed the change.  
- Then I switched back to `main` and edited the same file in a different way, committing again.  
- When I tried to merge the branch, Git gave a **merge conflict**.  
- I opened the file, fixed the conflict manually, staged the file, and committed the resolution.  

---
