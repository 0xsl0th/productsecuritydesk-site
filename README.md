# Product Security Desk landing page

Dependency-free static landing page for the initial CRA Reporting Readiness Sprint.

Production URL: `http://productsecuritydesk.com` until the GitHub Pages TLS certificate is active.

The public GitHub Pages source is the separate `0xsl0th/productsecuritydesk-site` repository. The wider business workspace remains private.

## Local preview

From the directory containing `index.html`:

```sh
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment notes

- Switch the canonical and social-sharing URLs to HTTPS after GitHub Pages issues the custom-domain certificate.
- Keep analytics and contact forms disabled until their privacy and data-handling terms are approved.
