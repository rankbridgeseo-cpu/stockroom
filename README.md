# Stockroom — luxury storefront (GitHub Pages)

Static frontend only; the backend remains in your private Google Apps Script project.

1. Publish this repository using **Settings → Pages → Deploy from a branch → main / (root)**.
2. Deploy the separate Stockroom API Worker from the private full package.
3. Edit `config.js` and set `apiBase` to the published `https://...workers.dev` address.
4. Do **not** upload `Code.gs`, private `Index.html`, or private project data to this repository.

Product photos, cart/WhatsApp checkout, and private order links use the Worker bridge.
