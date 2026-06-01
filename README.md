# GoldVision Legal Pages

Static site hosting Privacy Policy and Terms of Service for the GoldVision iOS app.

## Deploy to GitHub Pages

1. Create a new **public** GitHub repository named `goldvision-legal`
2. Push this folder's contents to the repo root:

```bash
cd legal
git init
git add .
git commit -m "Add privacy policy and terms of service"
git remote add origin https://github.com/ghassanjaam/goldvision-legal.git
git push -u origin main
```

3. In the GitHub repo → **Settings → Pages**
   - Source: `Deploy from a branch`
   - Branch: `main` / `/ (root)`
   - Click **Save**

4. Your URLs will be live in ~60 seconds:
   - **Home:** `https://ghassanjaam.github.io/goldvision-legal/`
   - **Privacy Policy:** `https://ghassanjaam.github.io/goldvision-legal/privacy.html`
   - **Terms of Service:** `https://ghassanjaam.github.io/goldvision-legal/terms.html`

## Use in App Store Connect

- **Privacy Policy URL:** `https://ghassanjaam.github.io/goldvision-legal/privacy.html`
- **Support URL:** `https://ghassanjaam.github.io/goldvision-legal/`

## Update in-app LegalView

Replace the static text in `LegalView.swift` with a WKWebView or SafariView pointing to the live URLs, or keep the in-app text as a mirror — both are acceptable.
