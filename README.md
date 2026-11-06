# SharinoWeb

Sharinos is a static website for an independent European car enthusiast garage.

## Local preview

Open `public/index.html` in a browser.

## Cloudflare Workers

The site is configured as a static asset Worker in `wrangler.jsonc`. Deploy with:

```sh
npx wrangler deploy
```

## Contact page

The contact form opens the visitor's default email app with an enquiry addressed to Sharinos. They review and send the message from their email app. No server-side email service or Worker secrets are required.