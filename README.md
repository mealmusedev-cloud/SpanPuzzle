# Span website

The home page, Support page, Privacy Policy, and Terms of Use for Span, ready for GitHub Pages.

| Page | File | Paste into App Store Connect as |
| --- | --- | --- |
| Home | `index.html` | Marketing URL (optional) |
| Support | `support.html` | Support URL |
| Privacy Policy | `privacy.html` | Privacy Policy URL |
| Terms of Use | `terms.html` | (Optional) link at the end of the app description |

## Details used

- Developer: **MealMuse Dev**
- Contact: **mealmusedev@gmail.com**
- Governing law: **State of Washington, United States**

The in-app copies (`MyApp/Resources/Legal/PrivacyPolicy.md` and `TermsOfUse.md`) use the same details. If you change anything here, change it there too.

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
