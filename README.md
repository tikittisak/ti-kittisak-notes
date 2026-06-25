# ti.career public site

Static public archive for ti.kittisak thinking notes.

## Pages

- `thinking-notes/ai-business-model/type-of-value-ai-era/`
- `thinking-notes/ai-business-model/type-of-value-ai-era/social/fb-linkedin.html`

## Publish

This folder is intentionally separated from the private `ti.career` vault.
Publish only this `public-site/` folder to GitHub Pages.

## GitHub Pages setup

1. Create a new public GitHub repository named `ti-kittisak-notes`.
2. Add the repository as this folder's `origin`.
3. Push `main`.
4. In GitHub: `Settings` -> `Pages` -> `Build and deployment` -> `Deploy from a branch`.
5. Select branch `main` and folder `/ (root)`.

```bash
git remote add origin https://github.com/<user>/ti-kittisak-notes.git
git push -u origin main
```

The published note URL will look like:

```text
https://<user>.github.io/ti-kittisak-notes/thinking-notes/ai-business-model/type-of-value-ai-era/
```

If a custom domain is added later, the target URL can become:

```text
https://ti.career/thinking-notes/ai-business-model/type-of-value-ai-era/
```
