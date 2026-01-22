# How to Host Your Portfolio on GitHub

Since I cannot directly access your GitHub account, follow these steps to host your site for free using GitHub Pages.

## Option 1: Using Terminal (Recommended)

1.  **Create a New Repository on GitHub**:
    *   Go to [github.com/new](https://github.com/new).
    *   Name it `portfolio` (or `username.github.io`).
    *   Make sure it is **Public**.
    *   Do **not** add a README, .gitignore, or license (we have them).
    *   Click **Create repository**.

2.  **Push Your Code**:
    Open your terminal and run the following commands inside the `portfolio-website` folder:

    ```bash
    # If git is not working, you might need to install XCode command line tools first:
    # xcode-select --install
    
    git init
    git add .
    git commit -m "Initial commit"
    git branch -M main
    git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
    git push -u origin main
    ```

## Option 2: Web Upload (Easiest if Git fails)

1.  Create a new repository on GitHub (steps above).
2.  Click the link that says **"uploading an existing file"** in the Quick setup box.
3.  Drag and drop **all files** from the `portfolio-website` folder (`index.html`, `style.css`, `script.js`, `README.md`, etc.) into the browser window.
4.  Commit the changes.

## Enable GitHub Pages

1.  Go to your repository **Settings**.
2.  Click **Pages** in the left sidebar.
3.  Under **Build and deployment** > **Source**, select **Deploy from a branch**.
4.  Under **Branch**, select `main` and `/ (root)`.
5.  Click **Save**.

Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/` in a few minutes!
