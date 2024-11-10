# My Resume on GitHub Pages

Follow this guide to upload your HTML and CSS files to GitHub and make your resume live on GitHub Pages.

## Step 1: Create a GitHub Repository

1. **Log in to GitHub** and click the **+** icon in the top-right corner.
2. Select **New repository**.
3. Name your repository (e.g., `my-resume`) and optionally add a description.
4. For visibility, select **Public** to make it accessible by anyone.
5. Leave the “Add a README file” and other templates unchecked for now.
6. Click **Create repository**.

---

## Step 2: Upload Files to the Repository

You have two options for uploading files:

### Option 1: Direct Upload on GitHub

1. Open your new repository.
2. Click **Add file** > **Upload files**.
3. Drag and drop your `index.html` and `style.css` files into the upload area.
4. Add a commit message like “Initial resume upload.”
5. Click **Commit changes** to add the files to the repository.

### Option 2: Upload via Git (If You Have Git Installed)

1. Open a terminal on your computer.
2. Navigate to the directory where your `index.html` and `style.css` files are saved.
3. Initialize a new Git repository:

    ```bash
    git init
    ```

4. Add the remote GitHub repository:

    ```bash
    git remote add origin https://github.com/your-username/my-resume.git
    ```

    Replace `your-username` and `my-resume` with your GitHub username and repository name.

5. Add your files, commit, and push to GitHub:

    ```bash
    git add .
    git commit -m "Initial resume upload"
    git branch -M main
    git push -u origin main
    ```

---

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub.
2. Click on **Settings** in the top menu.
3. Scroll down to the **GitHub Pages** section.
4. Under **Source**, select the branch as `main` and the folder as `root`.
5. Click **Save**.

GitHub will provide a URL for your site, like `https://your-username.github.io/my-resume`. It may take a few minutes for the site to become live.

---

## Step 4: Access Your Resume Online

Visit the URL provided in the GitHub Pages settings to view your resume live. Any updates you make to `index.html` or `style.css` and push to GitHub will automatically refresh on the live site.
