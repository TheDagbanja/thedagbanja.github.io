# Simon Dagbanja — Researcher Portfolio

A single-page, fully responsive academic profile (SAR remote sensing, InSAR,
few-shot learning). Pure HTML/CSS/JS in one file (`index.html`) — no build step,
no dependencies — so it hosts free on GitHub Pages.

## Files
- `index.html` — the whole site
- `profile.jpg` — your hero photo (already converted from the HEIC you sent)
- `cv.pdf` — **add this yourself** to enable the CV links (optional)

## ✏️ Make it yours
Open `index.html` and look for the `EDIT:` comments. Update:
- Your name, research one-liner, and affiliation (Hero)
- About bio and the side facts
- **Research** interests (already tailored to SAR / InSAR / few-shot)
- **Projects** — replace placeholders with your real projects
- **Publications** — your papers/preprints (your name is `<u>underlined</u>`)
- **Background** — education & experience
- Email and academic links (Google Scholar, ORCID, GitHub, LinkedIn) in the Hero and Contact
- Drop a `cv.pdf` in this folder to make the "CV" buttons work
- To change the photo, replace `profile.jpg` (keep the name, or update the `<img src>`).

## 🚀 Publish on GitHub Pages (free)

### Option A — website (easiest, no commands)
1. Create a GitHub account (if you don't have one).
2. Click **New repository**. Name it **`<your-username>.github.io`**
   (e.g. `simondagbanja.github.io`) — this gives you the clean URL `https://<your-username>.github.io`.
   Set it to **Public**.
3. On the new repo page, click **Add file → Upload files**, drag in `index.html`
   (and `README.md`, and your photo if you added one), then **Commit changes**.
4. Wait ~1 minute, then visit **https://<your-username>.github.io** — you're live.

> If you name the repo something else (e.g. `portfolio`), it still works, just at
> `https://<your-username>.github.io/portfolio/`. In that case go to
> **Settings → Pages → Build and deployment → Source: Deploy from a branch → main / root → Save**.

### Option B — command line (Git)
```bash
cd C:/Users/Simon/portfolio
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
git push -u origin main
```
Then open `https://<your-username>.github.io`.

## 🌐 Custom domain (optional, later)
In **Settings → Pages → Custom domain**, enter your domain and add the DNS records GitHub
shows you. HTTPS is provided automatically.

## Updating later
Edit `index.html`, then re-upload (Option A) or `git commit` + `git push` (Option B).
Changes go live in about a minute.
