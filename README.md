# Teluvo Privacy Policy Site

Static privacy policy page for App Store Connect.

## Files

- `privacy.html` - public privacy policy page URL target
- `index.html` - redirects to `privacy.html`

## Deploy

Cloudflare Pages:

```bash
npx wrangler pages deploy /Users/ylkj/teluvo-privacy-policy-site --project-name teluvo-privacy-policy
```

After deploy, use the `privacy.html` URL in App Store Connect.
