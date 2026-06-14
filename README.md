# SidelineLabz — Coming Soon

Coming soon page for [sidelinelabz.com](https://sidelinelabz.com).

Built with plain HTML/CSS/JS. No dependencies, no build step.

---

## Files

- `index.html` — the full page (self-contained)
- `CNAME` — tells GitHub Pages to serve this at sidelinelabz.com

---

## Deploy to GitHub Pages

1. Push these files to a GitHub repo (e.g. `sidelinelabz-site`).
2. Go to **Settings → Pages**.
3. Set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**.
4. Save. GitHub will publish the site in about a minute.

The CNAME file is already in the repo, so GitHub Pages will automatically
configure the custom domain once you point your DNS at GitHub.

---

## Point sidelinelabz.com at GitHub Pages

In your domain registrar (wherever you bought sidelinelabz.com), add these
DNS records:

**For the root domain (sidelinelabz.com):**

| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |

**For www.sidelinelabz.com (optional):**

| Type | Name | Value |
|------|------|-------|
| CNAME | www | z668hkhgvv-glitch.github.io |

DNS changes take anywhere from a few minutes to 24 hours to propagate.
Once they do, GitHub Pages will issue a free SSL certificate automatically.

---

## Update the page

Edit `index.html` directly in GitHub (tap the pencil icon) or clone and push.
No build tools needed — what you edit is what the site serves.

---

## SidelineLabz product

**SnapChart** — sideline play charting for iPad.
Repo: https://github.com/z668hkhgvv-glitch/SnapChart
Live app: https://z668hkhgvv-glitch.github.io/SnapChart/
