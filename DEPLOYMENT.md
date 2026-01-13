# Deployment Guide

This guide explains how to deploy your Loyalty CRM GitBook documentation to GitHub and make it accessible online.

## Prerequisites

- Git installed on your computer
- GitHub account
- Node.js (optional, for local preview)

---

## Option 1: Deploy to GitHub Pages (Recommended)

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the **+** icon in the top right and select **New repository**
3. Name your repository (e.g., `loyalty-crm-docs`)
4. Choose **Public** (required for free GitHub Pages)
5. **Do NOT** initialize with README (we already have one)
6. Click **Create repository**

### Step 2: Initialize Git and Push

Open your terminal/command prompt and navigate to the gitbook folder:

```bash
# Navigate to the gitbook directory
cd loyalty-gitbook

# Initialize git repository
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit - Loyalty CRM GitBook documentation"

# Add your GitHub repository as remote (replace with your URL)
git remote add origin https://github.com/YOUR_USERNAME/loyalty-crm-docs.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (gear icon)
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select **main** branch
5. Select **/ (root)** as the folder
6. Click **Save**

Your documentation will be available at:
`https://YOUR_USERNAME.github.io/loyalty-crm-docs/`

---

## Option 2: Deploy to GitBook.com

### Step 1: Create GitBook Account

1. Go to [GitBook.com](https://www.gitbook.com/)
2. Sign up for a free account
3. Connect your GitHub account

### Step 2: Import from GitHub

1. In GitBook dashboard, click **New Space**
2. Select **Import from GitHub**
3. Choose your repository
4. GitBook will automatically sync and build your documentation

---

## Option 3: Deploy to Netlify

### Step 1: Build Static Files (Optional)

If you want to build locally first:

```bash
# Install GitBook CLI globally
npm install -g gitbook-cli

# Install dependencies
gitbook install

# Build static files
gitbook build

# The output will be in _book/ folder
```

### Step 2: Deploy to Netlify

1. Go to [Netlify](https://www.netlify.com/)
2. Sign up/Log in
3. Click **New site from Git**
4. Connect your GitHub repository
5. Set build settings:
   - Build command: `gitbook build` (or leave empty if pre-built)
   - Publish directory: `_book` (or root if not using GitBook CLI)
6. Click **Deploy site**

---

## Option 4: Deploy to Vercel

### Step 1: Create Vercel Account

1. Go to [Vercel](https://vercel.com/)
2. Sign up with your GitHub account

### Step 2: Import Project

1. Click **New Project**
2. Import your GitHub repository
3. Vercel will auto-detect settings
4. Click **Deploy**

---

## Local Preview

To preview your GitBook locally before deploying:

### Using GitBook CLI

```bash
# Install GitBook CLI
npm install -g gitbook-cli

# Navigate to your gitbook folder
cd loyalty-gitbook

# Install plugins
gitbook install

# Start local server
gitbook serve

# Open http://localhost:4000 in your browser
```

### Using a Simple HTTP Server

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx serve .

# Open http://localhost:8000 in your browser
```

---

## Updating Documentation

After making changes to your documentation:

```bash
# Stage changes
git add .

# Commit changes
git commit -m "Update documentation"

# Push to GitHub
git push

# If using GitHub Pages, changes will auto-deploy
# If using GitBook.com with GitHub sync, changes will auto-sync
```

---

## Troubleshooting

### Pages Not Loading

- Ensure GitHub Pages is enabled in repository settings
- Check that SUMMARY.md is properly formatted
- Verify all file paths in SUMMARY.md are correct

### Build Errors

- Check for syntax errors in markdown files
- Ensure book.json is valid JSON
- Verify all linked files exist

### Images Not Displaying

- Use relative paths for images
- Store images in an `assets` or `images` folder
- Reference with: `![Alt text](./assets/image.png)`

---

## File Structure

```
loyalty-gitbook/
├── README.md              # Homepage
├── SUMMARY.md             # Table of contents
├── book.json              # GitBook configuration
├── .gitignore             # Git ignore file
├── DEPLOYMENT.md          # This deployment guide
└── modules/               # Documentation modules
    ├── account-management/
    ├── dashboard/
    ├── customer-modules/
    ├── tenants/
    ├── referral-group/
    ├── main-settings/
    ├── campaigns/
    ├── rewards/
    ├── mall-management/
    ├── news-updates/
    ├── rsvp/
    ├── reports/
    ├── communications/
    ├── business-intelligence/
    ├── survey/
    └── pos-purchase/
```

---

## Support

For issues with:
- **GitBook**: Visit [GitBook Documentation](https://docs.gitbook.com/)
- **GitHub Pages**: Visit [GitHub Pages Documentation](https://docs.github.com/pages)
- **This Manual**: Contact Fireworks Solutions Sdn Bhd
