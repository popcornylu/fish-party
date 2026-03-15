# Fishing Game

## Dev Server

Run the local dev server on port 8165:

```
uv run python -m http.server 8165
```

## Project Structure

- Single-page game: `index.html` (all HTML/CSS/JS inline)
- Python venv managed by `uv`
- Deployed to GitHub Pages via `.github/workflows/deploy.yml`
