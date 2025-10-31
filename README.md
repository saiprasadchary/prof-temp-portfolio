# Professor Portfolio (Template)

**1-Click Start:** https://github.com/saiprasadchary/prof-temp-portfolio/generate

## How to use (Professor)
1. Click **Use this template** (link above).
2. Name your repo (e.g., `prof-portfolio`), pick **Public**, then **Create**.
3. Go to **Settings → Pages**:
   - Source: **Deploy from a branch**
   - Branch: **main** (/**root**)
   - Save → wait for the green “Deployed” badge.
4. Open the site at `https://<your-username>.github.io/<repo-name>/`.

### Customize
- Edit `index.html` → the `const professor = { ... }` block:
  - `email`, `headshotUrl` (drop your image in **Images/**), `socials`, and `googleFormUrl` (or keep mailto).
- Replace images in **Images/** to your branding.
- (Optional) Update `<meta>` tags and JSON-LD to your profile links.

### Notes
- This site uses **hash routes** (`#research`, `#teaching`) so it works out-of-the-box on GitHub Pages.
- No build step required; everything is plain HTML/CSS/JS + Tailwind CDN.
