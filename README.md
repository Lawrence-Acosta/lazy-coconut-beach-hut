# Lazy Coconut Beach Hut

A responsive HTML + CSS profile/landing page for mobile, tablet, and desktop.

## Files
- `index.html` — page content and social links
- `style.css` — responsive styling
- `push-to-github.ps1` — optional Windows PowerShell publishing helper

## Customize the links
Open `index.html` and replace the `href` values:
- Google Profile: `https://share.google/lJbeV7HoV72IwAJEE`
- Facebook Page: `https://www.facebook.com/share/1JpLmMYRUy/`
- Rental Facebook: currently the same URL because the two Facebook links supplied were identical.

If you have a separate rental page URL, replace the third Facebook URL.

## Publish with GitHub Pages

1. Create a new **public** repository on GitHub, for example `lazy-coconut-beach-hut`.
2. Do not initialize it with a README, license, or `.gitignore` (this keeps the first push simple).
3. Install Git for Windows if `git --version` does not work in PowerShell.
4. Extract this folder to your computer.
5. Open PowerShell in this folder.
6. Run:

```powershell
git init
git branch -M main
git add index.html style.css README.md
git commit -m "Create Lazy Coconut Beach Hut website"
git remote add origin https://github.com/YOUR-USERNAME/lazy-coconut-beach-hut.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username and change the repository name if you used a different one.

### Turn on GitHub Pages
1. Open your repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**.
5. Click **Save**.
6. Wait a minute or two. Your site address will be:

`https://YOUR-USERNAME.github.io/lazy-coconut-beach-hut/`

Use your actual username and repository name.

## PowerShell helper
You can also run `.\push-to-github.ps1` from PowerShell. It asks for your GitHub repository URL, then initializes Git, commits the files, and pushes to `main`.
