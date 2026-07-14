# Ansh Limbani — Portfolio

Personal portfolio site for Ansh Limbani, Founder of Ark Infotech. Single-page site built with plain HTML/CSS/JS and a Three.js ambient background — no build step, no dependencies to install.

## Live locally

Just open `index.html` in a browser. That's it.

## Put it on GitHub + go live for free (GitHub Pages)

### 1. Create the repo
- Go to [github.com/new](https://github.com/new)
- **Repo name:** if you want it at `https://ansh<username>.github.io`, name the repo exactly `<your-github-username>.github.io`. If you'd rather it live at a path like `https://<username>.github.io/portfolio`, name it whatever you want (e.g. `portfolio`) instead.
- Keep it **Public** (required for free GitHub Pages).
- Don't add a README/gitignore from GitHub's UI — you already have this one.

### 2. Push this folder to it
Open a terminal in this folder and run:

```bash
git init
git add .
git commit -m "Initial commit — portfolio site"
git branch -M main
git remote add origin https://github.com/<your-github-username>/<repo-name>.git
git push -u origin main
```

### 3. Turn on GitHub Pages
- In your repo on GitHub, go to **Settings → Pages**
- Under **Build and deployment → Source**, choose **Deploy from a branch**
- Branch: `main`, folder: `/ (root)` → **Save**
- Wait ~1 minute, then your site is live at the URL GitHub shows you (either `https://<username>.github.io` or `https://<username>.github.io/<repo-name>`)

## Updating the site later

Edit `index.html`, then:

```bash
git add .
git commit -m "Update portfolio"
git push
```

GitHub Pages redeploys automatically within a minute or two.

## Notes for Ansh

- Skill proficiency percentages in the Skills section are placeholders — adjust them to be accurate.
- Project cards currently link to a pre-filled email ("Ask for a demo"). Swap those for real GitHub/itch.io/live-demo links once you have them.
- Add real screenshots or a project image if you want the cards to feel less empty.
