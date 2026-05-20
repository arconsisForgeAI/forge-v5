# arconsis Forge — Website V5

Live preview of the V5 redesign for [arconsis Forge](https://forge.arconsis.com).

**Password-protected preview** — JS gate with shared password.

## Files

- `arconsis-forge-v5.html` — Main landing page (V5 redesign)
- `index.html` — Redirect to V5
- `blog.html` — Media Hub
- `amp-v4.html` — Agentic Migration Platform product page
- `paperclip4enterprise-v4.html` — Paperclip4Enterprise product page
- `data-protection-v4.html`, `imprint-v4.html`, `information-obligation-v4.html` — Legal pages

## Updating

Local master lives at `~/Desktop/Forge Website/arconsis-forge-v5.html`.

To deploy an update:

```bash
cd /path/to/forge-v5
cp ~/Desktop/Forge\ Website/arconsis-forge-v5.html .
# re-inject password gate if file was re-exported clean
git add -A && git commit -m "Update v5 …" && git push
```

GitHub Pages auto-deploys from `main` branch root.
