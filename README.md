# Memact LandingPage

Version: `v2.0`

This is the public landing page for Memact. Actual version under development: https://github.com/Memact/Interface

Memact is positioned as:

```text
Cite Your Thoughts.
```

The landing page is intentionally static and Render-ready. It shows Memact as a simple product: type a thought, get a cited answer backed by links from what the user read, watched, searched, and revisited.

## What This Page Shows

- a short product-heavy Memact hero
- an interactive "cite this thought" demo
- real clickable citation links
- a simple three-step product flow
- strict visual consistency with the current Memact Interface style

## Local Preview

```powershell
cd C:\Users\sujay\Downloads\memact_ai\LandingPage
python -m http.server 8000 --bind 127.0.0.1
```

Open:

```text
http://127.0.0.1:8000
```

## Render Deployment

`render.yaml` is configured as a static site.

Use the repo root as the static publish path.

Render can build with:

```text
echo "Memact landing ready"
```

## Design Rules

- minimal and uncluttered
- `#00011B` plus white only
- mobile-first and safe-area aware
- no unsupported claims
- every demo answer includes citation links
- no heavy architecture explanation on the landing page

## License

See `LICENSE`.
