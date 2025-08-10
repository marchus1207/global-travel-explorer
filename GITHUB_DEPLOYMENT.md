# GitHub Pages Deployment Guide

Follow these steps to deploy your Global Travel Explorer site to GitHub Pages:

## Step 1: Create a new GitHub repository

1. Go to [GitHub](https://github.com) and sign in (or create an account)
2. Click the "+" icon in the top-right corner and select "New repository"
3. Name your repository (e.g., `global-travel-explorer`)
4. Add a description (optional)
5. Choose "Public" visibility
6. Check "Add a README file"
7. Click "Create repository"

## Step 2: Upload your files

### Option A: Using GitHub Desktop
1. Install [GitHub Desktop](https://desktop.github.com/) if you haven't already
2. Clone your new repository to your computer
3. Copy all your project files to the cloned repository folder
4. In GitHub Desktop, commit your changes with a message like "Initial commit"
5. Click "Push origin" to upload to GitHub

### Option B: Using Git command line
1. Open a terminal/command prompt in your project folder
2. Run the following commands:
```
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR-USERNAME/global-travel-explorer.git
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings"
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait a few minutes for your site to be published

Your site will be available at: `https://YOUR-USERNAME.github.io/global-travel-explorer/`

## Step 4: Add a custom domain (optional)

1. In your repository's "Settings" > "GitHub Pages" section
2. Under "Custom domain", enter your domain name
3. Click "Save"
4. Configure your domain's DNS settings to point to GitHub Pages
5. Wait for DNS propagation (can take up to 24 hours)

## Updating Your Site

To update your site, simply commit and push your changes to the main branch. GitHub Pages will automatically rebuild and deploy your site within a few minutes.
