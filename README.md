# Personal rclone OAuth information pages

Files:
- `index.html` — homepage
- `privacy.html` — privacy policy

## Before publishing
1. Replace `yogi.317.ys@gmail.com` in both HTML files with an email address you are comfortable publishing.
2. Review the wording and change anything that does not accurately describe your setup. In particular, keep the statements about storage, sharing, and use truthful.
3. Do not put OAuth client secrets, refresh tokens, or other credentials in these files.

## Publish with GitHub Pages
1. Create a GitHub repository (public is simplest for GitHub Pages).
2. Upload `index.html` and `privacy.html` to the repository root.
3. In repository Settings → Pages, choose deploy from the `main` branch and `/ (root)`.
4. Wait for GitHub Pages to publish. Your URLs will look like:
   - `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`
   - `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/privacy.html`
5. Open both URLs in a private/incognito window to verify they are publicly accessible.
6. In Google Auth Platform → Branding, enter the homepage URL and privacy-policy URL. If Google asks for an authorized domain, use the domain portion required by the console (for GitHub Pages this is typically `YOUR-USERNAME.github.io`).
7. Save, then retry publishing from Audience.

These pages do not guarantee Google will approve publishing or remove every verification requirement. Follow any additional requirements shown in Google Cloud Console.
