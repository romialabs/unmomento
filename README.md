# Un Momento website

## How editing works

1. Edit pages at **app.pagescms.org** (sign in with GitHub, open this repo). You only edit **drafts**.
2. A minute after saving, check the preview at `https://romialabs.dev/unmomento/preview/` (yellow "PREVIEW" bar on top).
3. When it looks right: GitHub → this repo → **Actions** → **Publish site** → **Run workflow**. The live site updates in about a minute.

Company name and support email live in **Site settings** (`_data/settings.yml`) and update on every page at once. Settings and images take effect immediately, without Publish.

## App Store Connect URLs

- Privacy Policy: `https://romialabs.dev/unmomento/privacy/`
- Support: `https://romialabs.dev/unmomento/support/`

## Layout

- `pages/`: live pages (only changed by Publish)
- `drafts/`: draft pages (what the editor changes)
- `_layouts/default.html`, `assets/style.css`: look and feel
- `.github/workflows/`: `deploy.yml` builds live + preview; `publish.yml` is the Publish button

Keep the privacy policy in sync with the app: if the app ever sends data off the device, update it first.
