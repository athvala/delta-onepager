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

Committed in `fonts/`:

- `Inter-400/500/600/700.ttf` — [Inter](https://rsms.me/inter/) v4.1 (SIL OFL 1.1)
- `PlexMono.ttf` — [IBM Plex Mono](https://github.com/IBM/plex) Regular (SIL OFL 1.1)
