# Tip QR Codes

Tip QR Codes is a lightweight, mobile friendly tip jar built for musicians, bands, and performers who want fast QR codes without apps, logins, or nonsense.

It runs entirely as a static page on GitHub Pages and includes a built in admin mode so any act can customize it on the fly.

## What it does
- Displays clean, scannable QR codes for tips and links
- Built in admin mode for full control
- Add unlimited payment or promo links
- Edit page title, subtitle, genre, and rotating tip jokes
- Choose background themes and visual vibes
- Saves settings locally per device
- Export and import configs so other acts can reuse it instantly

## Admin mode

Open the page with `?admin=1` at the end of the URL.

Example  
https://petesimple.github.io/tip-qr-codes/?admin=1

From there you can:
- Add, remove, and reorder QR cards
- Customize jokes and rotation timing
- Switch genres and background styles
- Export a config or share a single setup link

## PWA install and offline support

Tip QR Codes can also be installed like an app (PWA) so it feels native on phones and tablets.

What you get:
- Add to Home Screen install on iPhone and Android
- Standalone app style (no browser chrome)
- Offline friendly after first load (great for venues with questionable WiFi)

Files included for PWA support:
- `manifest.json` (app metadata)
- `service-worker.js` (offline caching)
- `icon-192.png` and `icon-512.png` (app icons)

How to install:
- iPhone (Safari): Share button → Add to Home Screen
- Android (Chrome): Install prompt or menu → Install app

Note:
- PWAs need HTTPS. GitHub Pages is perfect for that.
- Offline works after the page has been loaded once on that device.

## Default example

The repo ships with Petesimple links as examples:
- Venmo
- Cash App
- PayPal
- Apple Music

These are just defaults. Replace everything and make it yours.

## How to publish on GitHub Pages
1. Create a repo and add `index.html` and `README.md`
2. Go to Settings → Pages
3. Source: Deploy from a branch
4. Branch: main, folder: /root
5. Save

Your site will be live at  
https://yourname.github.io/your-repo/

## Why this exists

Because tip jars should be:
- Easy to scan
- Easy to edit
- Easy to reuse
- And never require explaining how an app works between songs

Built for merch tables, music stands, tablets, and the gentle chaos of live gigs.
