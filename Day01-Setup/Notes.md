# Day 01 - Environment Setup

## Objectives
- Install Git and configure global settings
- Create DevOps-Revision-Journey repository
- Connect GitHub to VS Code

## Key Commands
```bash
git config --global user.name "LakshmiDeepthiMelam"
git config --global user.email "your_email@example.com"
git status
git add .
git commit -m "Initial commit"
git push origin main
Learnings

Understood Git configuration flow

Learned how to commit from VS Code

> Tip: Use proper markdown formatting (`#` for headings, `##` for subheadings, triple backticks for code) so your notes look organized on GitHub.

---

## Step 5 — Save the file

- Press **Ctrl + S** (or **File → Save**) to save `notes.md`.  

---

## Step 6 — Stage and commit in VS Code

There are **two ways** to do this:

### Option A — Using the Source Control GUI

1. Click the **Source Control icon** (branch with dot, left sidebar).  
2. You’ll see `Day01-Setup/notes.md` under **Changes**.  
3. Hover → click **+** to stage the file.  
4. Type a commit message in the box:
Added Day01 notes - Environment Setup
5. Click the **✔ Commit** icon.  
6. Push to GitHub:
- Click the three dots `⋯` → **Push**  
- OR open terminal and run `git push origin main`

---

### Option B — Using Terminal

1. Open VS Code terminal (**Ctrl + `**)  
2. Run:
```bash
git add Day01-Setup/notes.md
git commit -m "Added Day01 notes - Environment Setup"
git push origin main
