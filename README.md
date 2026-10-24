# RavenLab Print

Static GitHub Pages-ready storefront for RavenLab paper printing.

## Included

- Arabic / English / Kurdish (Sorani)
- Iraqi dinar pricing only
- Responsive dark RavenLab design
- Product configurator modal
- Business Cards
- Loyalty Cards
- Circular Stickers
- Random Sticker Packs
- Wholesale quantity tiers
- Ready-made / Custom sticker option
- Cart / order summary
- WhatsApp ordering

## Files

- `index.html`
- `styles.css`
- `app.js`
- `assets/`
  - `business-card.png`
  - `loyalty-card.png`
  - `circular-stickers.png`
  - `random-stickers.png`

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Upload all files and the `assets` folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save.
7. GitHub will provide the public Pages URL.

## Edit prices

Open `app.js` and find `productData`.

Each product has:

```js
basePrices:{50:...,100:...,200:...,500:...,1000:...}
```

Replace those values with your final IQD prices.

## WhatsApp

Current RavenLab WhatsApp:

`9647773685433`

Edit `WHATSAPP` at the top of `app.js` if needed.
