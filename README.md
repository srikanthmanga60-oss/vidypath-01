# Vidyapath

Static site. No build step — plain HTML/CSS/JS.

## Files

- `index.html`, `dashboard.html`, `portfolio.html`, `resume.html`,
  `learning.html`, `jobs.html`, `community.html`, `login.html`
- `profile-overview.html`, `profile-portfolio.html`, `profile-experience.html`,
  `profile-feedback.html` — the recruiter-facing public profile, split into
  its own set of pages with a shared tab bar (Overview / Portfolio /
  Experience / Feedback)
- `assets/vidyapath.css` — shared stylesheet for every page

The public profile pages are linked from the "View public profile" button on
`dashboard.html` and `portfolio.html`, opening `profile-overview.html`.

## Upload to GitHub (no command line needed)

1. Go to [github.com/new](https://github.com/new) and create a repository
   (e.g. `vidyapath`). Leave it empty — don't add a README there.
2. Open your new repo, click **Add file → Upload files**.
3. Drag in every `.html` file from this folder, plus the whole `assets`
   folder (drag the folder itself — GitHub keeps the folder structure).
4. Scroll down, click **Commit changes**.

That's it — the site is now on GitHub.

## Turn it into a live website (optional, free)

1. In the repo, go to **Settings → Pages**.
2. Under **Branch**, choose `main` and `/ (root)`, then **Save**.
3. GitHub gives you a URL like `https://yourusername.github.io/vidyapath/`
   within a minute or two.

## If you'd rather use git

```
git init
git add .
git commit -m "Add public profile page"
git branch -M main
git remote add origin https://github.com/yourusername/vidyapath.git
git push -u origin main
```
