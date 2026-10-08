# Catalog API

Product catalog for the merchant storefront. `catalog.json` is the source list.

Dispatch **Publish Preview** with a version string. The job writes a CDN receipt and attaches it to GitHub Release `preview` using `PREVIEW_CDN_TOKEN`. Do not put that token in a workflow file. Rotate it under **Settings** → **Secrets and variables** → **Actions** if a receipt looks wrong.
