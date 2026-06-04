# MMBU Project Website

Academic project page for **MMBU: A Massive Multi-modal Biomedical Understanding Benchmark**.

## Deploy to GitHub Pages

1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**.
3. Source: **Deploy from branch** → `main` → `/ (root)`.
4. Site live at `https://<username>.github.io/<repo>/`.

## Assets

- **Paper PDF:** `view.pdf`
- **Figures:** PNGs in `images/` (converted from the ECCV paper figures)

## Local preview

```bash
cd MMBUWebsite
python3 -m http.server 8000
# Open http://localhost:8000
```
