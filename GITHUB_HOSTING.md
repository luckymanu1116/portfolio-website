# How to Host Your Portfolio on GitHub

I have set up your local project as a Git repository. To get it online, follow these steps:

## 1. Create a Repository on GitHub
1. Go to [github.com/new](https://github.com/new).
2. Repository name: `portfolio-website` (or `username.github.io`).
3. Visibility: **Public**.
4. **Do not** initialize with README, .gitignore, or license (we already have files).
5. Click **Create repository**.

## 2. Link Your Local Code
Copy the commands shown on GitHub under "…or push an existing repository from the command line" and run them in your terminal. They will look like this:

```bash
git remote add origin https://github.com/YOUR_USERNAME/portfolio-website.git
git branch -M main
git push -u origin main
```

*(Replace `YOUR_USERNAME` with your actual specific GitHub username)*

## 3. Enable GitHub Pages
1. Go to your repository **Settings** tab.
2. Select **Pages** from the left sidebar.
3. Under **Source**, select **Deploy from a branch**.
4. Under **Branch**, select **main** and folder **/(root)**.
5. Click **Save**.

Wait a minute or two, and your site will be live at `https://YOUR_USERNAME.github.io/portfolio-website/`!
