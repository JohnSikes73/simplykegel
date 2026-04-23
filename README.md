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
5. Click **Save**. Wait 30–60 seconds. GitHub will show a banner: **"Your site is live at `https://<your-username>.github.io/simplykegel/`"**.

## Your URLs for App Store Connect

After deployment, your URLs will be:

- **Support URL:** `https://<your-username>.github.io/simplykegel/`
- **Privacy Policy URL:** `https://<your-username>.github.io/simplykegel/privacy.html`

Both URLs must be publicly reachable (open them in an Incognito/Private window to verify before pasting into App Store Connect).

## Updating the site later

Edit the files in the repo (GitHub's web UI works fine — click the pencil icon on any file), commit, and GitHub Pages redeploys automatically within a minute.
