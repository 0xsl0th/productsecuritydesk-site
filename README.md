# Product Security Desk landing page

Dependency-free static landing page for the initial CRA Reporting Readiness Sprint.

Production URL: `https://productsecuritydesk.com`

The public GitHub Pages source is the separate `0xsl0th/productsecuritydesk-site` repository. The wider business workspace remains private.

## Preview

From the repository root:

```sh
python3 -m http.server 8080 --directory site
```

Then open `http://localhost:8080`.

## Before public deployment

- Confirm that `hello@productsecuritydesk.com` receives mail or forwards to the founder.
- Replace the email CTA with the approved scheduling link when available.
- Update `privacy.html` with the selected hosting, email, scheduling, and analytics providers.
- Add the final canonical URL and social-sharing image metadata after DNS is configured.
- Keep analytics and contact forms disabled until their privacy and data-handling terms are approved.
