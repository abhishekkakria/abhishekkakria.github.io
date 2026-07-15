# Abhishek Kakria — PMM Portfolio

Static portfolio site. No build step, no dependencies — plain HTML/CSS.

## Structure

```
portfolio/
├── index.html                          # Homepage
├── css/style.css                       # Shared styles
├── case-studies/
│   ├── apac-expansion.html             # APAC case study
│   └── phonepe-sharemarket.html        # PhonePe case study
└── assets/
    ├── APAC_Expansion_Case_Study.pdf   # Downloadable deck
    └── PhonePe_ShareMarket_Case_Study.pdf
```

## Deploy on GitHub Pages (free)

1. Create a GitHub account if needed, then create a new **public** repository
   named exactly `<your-username>.github.io` (e.g. `abhishekkakria.github.io`).
   This makes the site live at the root URL with no path suffix.
2. Upload everything in this folder to the repo root (drag-and-drop on
   github.com works: Add file → Upload files), or via git:
   ```
   git init
   git add .
   git commit -m "Portfolio v1"
   git branch -M main
   git remote add origin https://github.com/<username>/<username>.github.io.git
   git push -u origin main
   ```
3. In the repo: Settings → Pages → Source: "Deploy from a branch" →
   Branch: `main`, folder `/ (root)` → Save.
4. Wait 1–2 minutes. Site is live at `https://<username>.github.io`.
5. Every future edit: change the file, commit/upload, it redeploys automatically.

## Before going live — fill these in

- Verify the LinkedIn and ArtStation URLs.
- Decide the SolarVista3D card: keep "in progress", or build the third page.
- Optional: custom domain (Settings → Pages → Custom domain) — a .com/.in
  domain costs ~₹800–1,000/yr and looks sharper on a CV.

## Editing tips

- All colors/fonts are CSS variables at the top of `css/style.css`.
- To add a case study: duplicate a page in `case-studies/`, swap the content,
  and add a `.dossier` card on `index.html`.
