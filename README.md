# CapyCapital

A single-page landing page for CapyCapital, an "unbothered AI for the Indian markets" concept site. Dark **navy-blue** theme (recolored from the original green palette) with an animated background canvas, live-typing hero line, and a few illustrative SVG charts/gauges.

## Project structure

```
capycapital/
├── .vscode/
│   ├── settings.json      # format-on-save, recommended Emmet setup
│   └── extensions.json    # recommended VS Code extensions
├── index.html             # the entire site (HTML + CSS + JS, single file)
├── .gitignore
└── README.md
```

## Running it locally

No build step — it's a static HTML file.

1. Open this folder in VS Code.
2. Install the recommended extensions when prompted (or install **Live Server** manually).
3. Right-click `index.html` → **Open with Live Server**.
   - Or just double-click `index.html` to open it directly in a browser.

## Pushing to GitHub

```bash
git init
git add .
git commit -m "Initial commit: CapyCapital site (navy theme)"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

## Theme

The color palette lives at the top of `index.html` inside `:root`:

```css
--bg-deep:#0B1220;
--bg-surface:#131F33;
--bg-surface-2:#1B2B45;
--line:#2A3B5C;
--text-muted:#93A3C6;
--text-faint:#5E6F93;
```

Gold accents (`--accent`) and the red/green up/down market indicators were kept as-is since they're semantic, not part of the background theme.
