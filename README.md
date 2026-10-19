# CarsBuyNSell – Landing Page

Static HTML site (no build step). Open `index.html` in a browser to preview.

## Files
- `index.html` – the whole page (styles inline, small script at the bottom for the car tabs and hero countdown)
- `assets/` – logo, hero image, app screenshot, QR code
- `assets/cars/` – put your car photos here

## Before going live, update in index.html
- Brochure link: search `https://drive.google.com/` and replace with your Drive share link
- Play Store link: search `https://play.google.com/store`
- App Store link: search `https://apps.apple.com/`
- Contact details: search `[PHONE NUMBER]`, `[EMAIL ADDRESS]`, `[WHATSAPP NUMBER]`
- Social / policy links: the `href="#"` links in the footer
- Car photos: each car card has a commented `<img>` line – uncomment it and match the file name

## Deploy to GitHub Pages
1. Create a new public repository on GitHub (e.g. `carsbuynsell-site`).
2. Upload `index.html`, `README.md` and the `assets` folder to the repository root.
3. Go to Settings → Pages → Build and deployment → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)` → Save.
4. After a minute the site is live at `https://<your-username>.github.io/carsbuynsell-site/`.

Custom domain: Settings → Pages → Custom domain, then add the DNS records GitHub shows you.
