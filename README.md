# Span website

The home page, Support page, Privacy Policy, and Terms of Use for Span, ready for GitHub Pages.

| Page | File | Paste into App Store Connect as |
| --- | --- | --- |
| Home | `index.html` | Marketing URL (optional) |
| Support | `support.html` | Support URL |
| Privacy Policy | `privacy.html` | Privacy Policy URL |
| Terms of Use | `terms.html` | (Optional) link at the end of the app description |

## Before publishing

Find and replace these placeholders in all four HTML files:

- `[DEVELOPER NAME]`
- `[CONTACT EMAIL]`
- `[STATE / COUNTRY]` (in `terms.html`)

Make the same changes in `MyApp/Resources/Legal/PrivacyPolicy.md` and `TermsOfUse.md` so the in-app copy matches.

## Publish

1. Create a new **public** repository on GitHub, for example `span`.
2. Upload everything in this folder to the root of the repository: the four HTML files, `style.css`, `icon.png`, `apple-touch-icon.png`, the `fonts` folder, and `.nojekyll` (press ⌘⇧. in Finder to show it).
3. In the repository, go to **Settings > Pages**, set **Source** to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. After a minute or two the site is live.

Your URLs will be:

- Home: `https://<your-username>.github.io/span/`
- Support: `https://<your-username>.github.io/span/support.html`
- Privacy Policy: `https://<your-username>.github.io/span/privacy.html`
- Terms of Use: `https://<your-username>.github.io/span/terms.html`
