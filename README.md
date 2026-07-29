# My Website — Setup Guide

This is a starter website built with **Jekyll** + the **Minimal Mistakes** theme, ready to host for free on **GitHub Pages**. You don't need to install anything — GitHub builds the site for you automatically.

## Step 1: Create the repository

1. Go to https://github.com and log in.
2. Click the **+** icon (top right) → **New repository**.
3. Name it **exactly**: `yourusername.github.io` (replace `yourusername` with your actual GitHub username — this exact naming is what makes it auto-publish).
4. Set it to **Public**.
5. Don't add a README/gitignore/license — leave it empty.
6. Click **Create repository**.

## Step 2: Upload these files

1. On your new (empty) repo page, click **"uploading an existing file"** (or use "Add file" → "Upload files").
2. Drag and drop **all the files and folders** from this starter kit into the upload box — keep the folder structure intact (`_posts`, `_data`, `assets`, `_config.yml`, `index.md`, `about.md`, `projects.md`, `essays.md`, `Gemfile`).
3. Scroll down, add a commit message like "Initial site setup," and click **Commit changes**.

## Step 3: Turn on GitHub Pages (only needed if repo isn't named username.github.io)

If you named the repo exactly `yourusername.github.io`, it publishes automatically — skip this step.

Otherwise:
1. Go to your repo → **Settings** → **Pages** (left sidebar).
2. Under "Build and deployment," set **Source** to `Deploy from a branch`.
3. Choose branch `main`, folder `/ (root)`, then **Save**.

## Step 4: Wait a minute, then visit your site

Your site will be live at:
```
https://yourusername.github.io
```
(or `https://yourusername.github.io/repo-name` if you used a different repo name)

It can take 1–3 minutes after the first push. Check the **Actions** tab in your repo to see if the build succeeded (green check) or failed (red X, with error details).

## Step 5: Personalize it

Before/after uploading, edit these files with your real info (you can edit any file directly on GitHub by clicking it, then the pencil ✏️ icon):

- **`_config.yml`** — replace `url`, email, LinkedIn, GitHub links with your real ones
- **`about.md`** — already filled with your info, but double check it
- **`projects.md`** — fill in the placeholder project descriptions
- **Add essays** — copy `_posts/2026-07-29-welcome-to-my-essays.md`, rename it, and write your own essay following the same format (delete or keep the sample)

## Adding a profile photo (optional)

1. Upload a photo into `assets/images/` and name it `avatar.jpg`.
2. It'll automatically show in your sidebar since `_config.yml` already points to it.

## Editing directly on GitHub (no software needed)

For all of this, you don't need to install anything on your computer. On GitHub.com:
- Click any file → pencil icon (✏️) → edit directly in the browser → commit changes at the bottom.
- To add a new file (like a new essay), go into the `_posts` folder → **Add file** → **Create new file**.

That's the entire workflow: edit or add a file → commit → site rebuilds automatically in about a minute.
