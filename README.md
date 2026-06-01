# abubakar-yousafzai.github.io

Personal portfolio site — single-page, plain HTML/CSS/JS, hosted on GitHub Pages.

## Local preview

```bash
cd ~/personal-site
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a public repo on GitHub named **exactly** `a-yousafzai.github.io` (must match your username).
2. From this directory:
   ```bash
   git init -b main
   git add .
   git commit -m "Initial portfolio site"
   git remote add origin git@github.com:a-yousafzai/a-yousafzai.github.io.git
   git push -u origin main
   ```
3. Go to **repo → Settings → Pages** and confirm Source is `Deploy from a branch` → `main` → `/ (root)`.
4. Site goes live at https://a-yousafzai.github.io within ~1 minute.

## Files

- `index.html` — content
- `styles.css` — all styling (dark theme, accent green)
- `script.js` — scroll reveal + animated background
