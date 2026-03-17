# Alam Zaib Portfolio

This folder contains a static portfolio website built with HTML and CSS.

## ✅ Make it public (GitHub Pages)
To share your portfolio with a link that anyone can access, you can host it using **GitHub Pages**.

### 1) Create a GitHub repository
1. Go to https://github.com and sign in (or create an account).
2. Click **New repository**.
3. Give it a name (e.g., `portfolio.Alam`) and set **Public**.
4. Leave all other settings default and create the repo.

### 2) Push your local project to GitHub
Run these commands in PowerShell from this folder:

```powershell
cd "C:\Users\CLASSIC\OneDrive\Desktop\portfolio.Alam"
git init
git add .
git commit -m "Initial portfolio upload"
# Replace <YOUR-USERNAME> and <YOUR-REPO> with your GitHub username and repo name
git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO>.git
git branch -M main
git push -u origin main
```

### 3) Enable GitHub Pages
1. Go to the repository on GitHub.
2. Click **Settings** > **Pages** (left sidebar).
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. In **Branch**, select `main` and choose `/ (root)`.
5. Click **Save**.

After a minute, GitHub will provide a link like:

```
https://<YOUR-USERNAME>.github.io/<YOUR-REPO>/
```

### Optional: Use Custom Domain
If you own a domain, you can add it in **Settings → Pages** under "Custom domain".

---

If you want, I can also help you configure an automated GitHub Actions workflow so the site deploys automatically when you push.