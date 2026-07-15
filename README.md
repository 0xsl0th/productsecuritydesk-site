# Product Security Desk landing page

Dependency-free static landing page for the initial CRA Reporting Readiness Sprint.

Production URL: `https://productsecuritydesk.com/`.

The public GitHub Pages source is the separate `0xsl0th/productsecuritydesk-site` repository. The wider business workspace remains private.

## Local preview

From the directory containing `index.html`:

```sh
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment notes

- Umami Cloud analytics uses the European Union data region and website ID `20941052-39b3-4d0e-a211-5fc59ed00aa9`.
- The tracker runs only on `productsecuritydesk.com` and `www.productsecuritydesk.com`, respects Do Not Track, and ignores URL fragments while retaining campaign query parameters.
- Conversion events are `calendly-click`, `sample-report-open`, and `email-copy`. Their `location` property identifies the CTA placement.
- Keep the privacy notice synchronized with any analytics, scheduling, hosting, or contact-flow changes.
