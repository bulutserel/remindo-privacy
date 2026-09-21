# Remindo — Privacy Policy (GitHub Pages)

Static Privacy Policy for App Store Connect. No custom domain required.

## Publish (one-time)

1. Create a **public** GitHub repo named `remindo-privacy` (empty, no README).
2. From this folder:

```bash
cd ~/Desktop/remindo-privacy
git init
git add .
git commit -m "Add Remindo privacy policy"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/remindo-privacy.git
git push -u origin main
```

3. GitHub → **Settings → Pages** → Deploy from a branch → `main` / `/ (root)` → Save.
4. Open: `https://YOUR_USERNAME.github.io/remindo-privacy/`
5. Paste that URL into App Store Connect → **Privacy Policy URL**.

Files:
- `index.html` — root Pages URL
- `privacy-policy.html` — same content (explicit path)
