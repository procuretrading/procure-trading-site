# Procure Trading Website

Simple one-page website for Procure Trading, LLC.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g., `procure-trading-site` or `procuretrading.github.io`)
2. Push all files in this folder to the repository
3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch**
5. Choose `main` branch and `/ (root)` folder
6. Click **Save**

Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a few minutes.

## Custom Domain (optional)

To use `procuretrading.com`:
1. In **Settings → Pages**, enter your custom domain
2. Add a CNAME record with your DNS provider pointing to `<your-username>.github.io`
3. GitHub will automatically configure HTTPS

## Files

```
├── index.html          # Main website (single page, all CSS inline)
├── images/
│   ├── logo.jpg        # Navigation logo (180x180)
│   └── logo-full.jpg   # About section logo (larger)
└── README.md           # This file
```

## Customization

- **Contact form**: The form currently uses a placeholder action. To make it functional, sign up at [Formspree](https://formspree.io) and replace `your-form-id` in the form action URL.
- **Colors**: Edit the CSS variables in `:root` at the top of the `<style>` block.
- **Content**: All text is directly in `index.html` — edit as needed.
