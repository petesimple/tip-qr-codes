# Tip QR Codes

A tiny GitHub Pages site that generates QR codes for tip links.

Current links
- Venmo: https://venmo.com/u/petesimple
- Cash App: https://cash.app/$petesimple
- PayPal: https://paypal.me/PeteLippincott

## How to publish on GitHub Pages
1. Create a repo and add index.html and README.md
2. Go to Settings - Pages
3. Source: Deploy from a branch
4. Branch: main, folder: /root
5. Save

Your site will be live at:
https://YOUR-USERNAME.github.io/YOUR-REPO/

## Adding more payment options
Edit the `TIPS` array inside index.html and add another item with:
- id
- name
- subtitle
- url
