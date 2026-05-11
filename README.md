# Timberhold marketing site

Three static files. No build step. No dependencies.

- `index.html` — landing
- `support.html` — FAQ and contact (use as the App Store Connect Support URL)
- `privacy.html` — privacy policy (use as the App Store Connect Privacy Policy URL)

## Deploying to GitHub Pages

1. Push these three HTML files to the root of a public repo (e.g. `timberhold-site` or any docs branch of an existing repo).
2. Repo → Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / folder: `/ (root)` → Save.
3. After ~1 minute, the site is live at `https://<your-user>.github.io/<repo>/`.

## App Store Connect URLs

| Field | Value |
|---|---|
| Support URL | `https://<your-user>.github.io/<repo>/support.html` |
| Marketing URL | `https://<your-user>.github.io/<repo>/` |
| Privacy Policy URL | `https://<your-user>.github.io/<repo>/privacy.html` |

(Or use a custom domain if you've configured one for the repo.)

## Customizing

- Email address is hardcoded as `roosbarney@gmail.com` in three places per file.
- Copyright holder is `Lance Dye` in the footers.
- Effective date on the privacy page is `May 11, 2026` — bump it whenever the policy materially changes.
