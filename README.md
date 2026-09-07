# Indie Agent Services

Lead-capture site for **Indie Agent Kit** (`boltdoesthis`) paid micro-work.

Ship landing pages and launch assets with agent-speed help. Clients email **boltdoesthis@gmail.com**. Fixed packages, honest indie rates, 48h turnaround after scope is clear.

Live URL (after Pages deploy): https://boltdoesthis.github.io/indie-agent-services/

## Packages

| Package | Price | What you get |
|---------|-------|----------------|
| Landing page from your README | $49 | One static landing HTML from your README/blurb |
| Launch pack | $79 | Landing + OG card (PNG/SVG) + tweet/LinkedIn blurbs |
| Custom agent skill pack | $99 | Small skill pack tuned to your product |

## Files

| File | Role |
|------|------|
| `index.html` | Static lead-capture page (HTML + CSS) |
| `README.md` | This file |

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
# Python
python3 -m http.server 8080

# Node (if you have npx)
npx --yes serve -p 8080
```

Then visit `http://localhost:8080`.

## Deploy (free)

### GitHub Pages (boltdoesthis / indie-agent-services)

1. Create a public repo named `indie-agent-services` under [github.com/boltdoesthis](https://github.com/boltdoesthis).
2. Push this folder as the repo root (or put files in `/docs` and set Pages source to `/docs`).
3. Settings → Pages → Deploy from branch → `main` / root (or `/docs`).
4. Site URL: `https://boltdoesthis.github.io/indie-agent-services/`

Example first push:

```bash
cd indie-agent-services
git init
git add index.html README.md
git commit -m "Initial Indie Agent Services lead-capture page"
git branch -M main
git remote add origin https://github.com/boltdoesthis/indie-agent-services.git
git push -u origin main
```

Then enable Pages on `main` / root.

### Cloudflare Pages

1. Push the same repo to GitHub/GitLab.
2. Cloudflare Dashboard → Workers & Pages → Create → Connect to Git.
3. Framework preset: **None**. Build command: empty. Output directory: `/` (repo root).
4. Deploy. Optional: attach a custom domain later.

## Related free tools

- https://boltdoesthis.github.io/readme-to-landing/
- https://boltdoesthis.github.io/changelog-to-og/
- https://github.com/boltdoesthis/indie-agent-ship-kit-teaser

## License

MIT. Indie Agent Kit / boltdoesthis.

## Brand

Public brand only: **Indie Agent Kit** / **boltdoesthis**. No personal identity in public copy.
