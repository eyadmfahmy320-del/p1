# Dragons Gaming Website

This folder contains a simple static website with `index.html`, `signin.html`, and `style.css`.

## Ready for GitHub Pages

1. Install Git on your computer.
2. Create a new GitHub repository.
3. Add this folder as a local Git repo, commit the files, and push to GitHub.
4. Enable GitHub Pages in the repository settings, using the `main` branch and root folder.

Once published, the site will be available at `https://<your-github-username>.github.io/<repository-name>/`.
# Dragons Website

This folder contains a simple HTML/CSS website.

## Files

- `index.html` – homepage for deployment
- `signin.html` – sign-in page
- `style.css` – site styling

## To publish on GitHub Pages

1. Install Git on your computer.
2. Create a new GitHub repository.
3. In this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
   git push -u origin main
   ```
4. In the GitHub repository settings, enable GitHub Pages from the `main` branch.
5. Your site will be available at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## Note

Images are currently referenced by local absolute paths. To make them work online, replace those with relative paths to image files stored in this folder or in an `images/` directory.
