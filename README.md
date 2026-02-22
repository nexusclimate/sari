# SARI SOFTWARE TECNOLOGIES

Landing page for SARI SOFTWARE TECNOLOGIES.

## Push to GitHub and go live

1. **Create a new repo on GitHub**
   - Go to [github.com/new](https://github.com/new)
   - Repository name: `sari` (or e.g. `sari-software`)
   - Leave “Add a README” unchecked (you already have one)
   - Create repository

2. **Push this folder**
   ```bash
   cd /Users/bastiaansenj/Library/CloudStorage/ProtonDrive-Jaap@jb-email.me-folder/Github/sari
   git remote add origin https://github.com/YOUR_USERNAME/sari.git
   git push -u origin main
   ```
   Replace `YOUR_USERNAME` with your GitHub username (and `sari` with the repo name if different).

3. **Turn on GitHub Pages**
   - In the repo: **Settings** → **Pages**
   - Under **Build and deployment**, **Source** choose **GitHub Actions**
   - Save (the workflow in `.github/workflows/pages.yml` will run on every push to `main`)

4. **Your site**
   - After the first push and once the workflow finishes:  
     **https://YOUR_USERNAME.github.io/sari/**  
   - (If you used a different repo name, replace `sari` in the URL.)
