# Deploy HZ Jewellery Website to Hostinger

This project is a static one-page website (`index.html` + `logo.png`), so deployment on Hostinger is very simple.

## 1) Prepare files
Make sure you have these in your project folder:
- `index.html`
- `logo.png`

Optional: add `favicon.ico` later if needed.

## 2) Log in to Hostinger
1. Go to [hpanel.hostinger.com](https://hpanel.hostinger.com)
2. Open your hosting plan/site.

## 3) Open File Manager
1. In hPanel, go to **Websites** → **Manage** (for your domain).
2. Open **File Manager**.
3. Navigate to `public_html`.

## 4) Upload website files
1. Delete Hostinger default files in `public_html` (for example, default `index.php`) if present.
2. Upload your `index.html` and `logo.png` directly into `public_html`.
3. Ensure the file name is exactly `index.html` (lowercase).

## 5) Verify the website
1. Open your domain URL in browser.
2. Hard refresh (`Ctrl+F5` / `Cmd+Shift+R`) to bypass cache.
3. Confirm logo loads and social buttons open correctly.

## 6) If logo is not visible
- Ensure the logo file is named exactly `logo.png`.
- Ensure it is uploaded in the same folder as `index.html` (`public_html`).

## 7) Optional: connect custom domain
If domain is not connected yet:
1. In Hostinger, open **Domains** / **DNS Zone**.
2. Point domain to Hostinger nameservers (if purchased outside Hostinger).
3. Wait for DNS propagation (can take up to 24 hours, usually faster).

## 8) Optional: SSL
In Hostinger hPanel:
- Go to **Security** → **SSL** and enable SSL for your domain.
- Visit `https://yourdomain.com`.

---

## Quick deploy checklist
- [ ] `index.html` uploaded to `public_html`
- [ ] `logo.png` uploaded to `public_html`
- [ ] domain opens homepage
- [ ] Instagram button works
- [ ] Facebook and WhatsApp placeholders intentionally point to `#`
