# 🚀 SIH2025 Contribution Guide

Welcome to the **SIH2025 Repository** 👋  
Follow these steps to set up Git, clone the repository, create your own branch, and push your contributions.

---

## 🛠️ Step 0: Setup Git (One-time only)

### Install Git  
👉 [Download Git](https://git-scm.com/downloads) and install.

Check version:  
```bash
git --version
```

### Configure Git with your GitHub account  
```bash
git config --global user.name "YourGitHubUsername"
git config --global user.email "YourGitHubEmail@example.com"
```

Verify your config:  
```bash
git config --global --list
```

---

## 📂 Step 1: Clone Repository
```bash
git clone https://github.com/pirates-of-mern/sih2025.git
cd sih2025
```

---

## 🌿 Step 2: Create Your Branch
```bash
git checkout -b your-branch-name
```
👉 Example:  
```bash
git checkout -b suryadeep-branch
```

---

## 📝 Step 3: Create Your File
Create a `.md` or `.txt` file with some content about yourself.

Example:  
```bash
echo "this is github intro file of pirates of mern team!!" > intro.md
```

(Or create the file manually inside the project folder)

---

## ➕ Step 4: Add File
```bash
git add intro.md
```

---

## 💬 Step 5: Commit Your Changes
```bash
git commit -m "Added intro file: intro.md"
```

💡 **Pro Tip:** Write clear & short commit messages.

---

## ☁️ Step 6: Push to GitHub
```bash
git push origin your-branch-name
```

👉 Example:  
```bash
git push origin suryadeep-branch
```

---

## ✅ Step 7: Create Pull Request
### this is alredy done if u have accepted github invite!!!
1. Go to the GitHub repository page.  
2. You’ll see a prompt to create a **Pull Request** for your branch.  
3. Click **Compare & pull request**.  
4. Add a short description of your changes.  
5. Submit the PR 🎉  

---

## 🔎 Useful Commands
Check current status:  
```bash
git status
```

See your commit history:  
```bash
git log --oneline
```

Switch to another branch:  
```bash
git checkout branch-name
```

---

## ⚡ Notes
- Always keep the **branch name same** in Step 2 and Step 6.  
- Make sure your GitHub email is verified.  
- Use meaningful filenames (e.g., `name.md`).  
- Commit messages should describe **what you changed/added**.  

---

Happy Contributing ❤️
