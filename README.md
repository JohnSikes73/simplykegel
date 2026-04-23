# Simply Kegel — Support & Privacy Site

Static site with two pages, hosted on GitHub Pages, used for:

- **Support URL** — `index.html` (contact, FAQ)
- **Privacy Policy URL** — `privacy.html`

Both are required for App Store submission.

## How to deploy (one-time, ~5 minutes)

1. Go to https://github.com/new and create a new **public** repo named `simplykegel`.
2. Upload `index.html`, `privacy.html`, and this `README.md` to the repo. The fastest way: on the new empty repo page, click **uploading an existing file** and drag these three files in. Commit directly to `main`.
3. In the repo, go to **Settings** → **Pages** (left sidebar).
4. Under **Build and deployment**, set:
   - **Source:** Deploy from a branch
   - **Branch:** `main` / `(root)`
5. Click **Save**. Wait 30–60 seconds. GitHub will show a banner: **"Your site is live at `https://JohnSikes73.github.io/simplykegel/`"**.

## Your URLs for App Store Connect

After deployment, paste these exact URLs into App Store Connect:

| Field in App Store Connect | URL to paste |
| --- | --- |
| **Support URL** | `https://JohnSikes73.github.io/simplykegel/` |
| **Privacy Policy URL** | `https://JohnSikes73.github.io/simplykegel/privacy.html` |
| **Marketing URL** (optional) | `https://JohnSikes73.github.io/simplykegel/` |

Before pasting, open both URLs in a private/incognito browser window to confirm they load. If you get a 404 immediately after enabling Pages, wait another minute — GitHub Pages takes up to ~2 minutes on first deploy.

## Updating the site later

Edit the files in the repo (GitHub's web UI works fine — click the pencil icon on any file), commit, and GitHub Pages redeploys automatically within a minute.
