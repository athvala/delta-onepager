# Delta by Simplified AI — One-Pager

Single-page A4 one-pager for Delta, built as print-oriented HTML.

## View in browser

Open `index.html` directly, or serve it:

```bash
python3 -m http.server 8000
```

then open http://localhost:8000.

## Render to PDF (WeasyPrint)

```bash
pip install weasyprint
weasyprint index.html delta-onepager.pdf
```

## Fonts

The stylesheet expects these files in `fonts/` (not committed):

- `fonts/Inter-400.ttf`, `Inter-500.ttf`, `Inter-600.ttf`, `Inter-700.ttf` — [Inter](https://rsms.me/inter/)
- `fonts/PlexMono.ttf` — [IBM Plex Mono](https://github.com/IBM/plex)

Without them the page falls back to system sans-serif / monospace.
