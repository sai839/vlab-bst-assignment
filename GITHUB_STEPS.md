# Quick Guide: GitHub Account, Repository & Upload

## A) Create a GitHub Account
1. Go to https://github.com and click **Sign up**.
2. Enter email → **Continue** → create password → choose username.
3. Verify email (check your inbox for the 6-digit code).
4. Skip personalization or choose defaults.

## B) Create a New Repository
1. Click your profile picture (top-right) → **Your repositories** → **New**.
2. Repository name: `vlab-bst-assignment` (or any name your instructor requires).
3. Choose **Public** (or **Private** if required).
4. Click **Create repository**.

## C) Upload the Assignment (Web UI)
1. On the new repo page, click **Add file** → **Upload files**.
2. Drag-and-drop the files from this folder:
   - `Assignment_BST_VLab.pdf`
   - `README.md`
   - `GITHUB_STEPS.md`
   - `images/bst_result.png`
3. Scroll down → add a commit message (e.g., "Add BST assignment") → **Commit changes**.
4. Copy the repository URL from your browser (e.g., `https://github.com/<your-username>/vlab-bst-assignment`) and submit it.

## D) Upload via Git (optional)
```bash
# One-time setup
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# In a terminal, from the folder that contains your files:
git init
git add .
git commit -m "Add BST assignment"
git branch -M main
git remote add origin https://github.com/<your-username>/vlab-bst-assignment.git
git push -u origin main
```
