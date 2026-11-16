# Zari Sutra by Himanshi

A lightweight, responsive sari storefront built with plain HTML, CSS, and JavaScript. No build step or package installation is required.

## Run locally

Open `index.html` in a browser, or serve this folder with any static file server.

## Configure WhatsApp

Open `index.html` and find this line near the bottom:

```js
const WHATSAPP_NUMBER = '';
```

Replace the empty string with the business number in international format using digits only. For example, an Indian number would start with `91`, with no `+`, spaces, or punctuation. The inquiry buttons will then open a direct chat with a prefilled message. Until configured, they open WhatsApp with the message ready to share.

## Deploy

This is a static site. Publish this folder as the site root using any static host:

- **GitHub Pages:** push this folder to a repository, then enable Pages for the branch and folder containing `index.html`.
- **Netlify:** import the repository; the included `netlify.toml` publishes the project root.
- **Vercel:** import the repository; the included `vercel.json` serves it as a static site.

There is no build command and no output directory to configure.

## Before launch

- Set the WhatsApp business number.
- Replace the sample collection descriptions and images with the business's current sari inventory and original product photos.
- Add actual business contact and social links if desired.

Product photos are currently loaded from Unsplash and fonts from Google Fonts, so those assets require an internet connection.
