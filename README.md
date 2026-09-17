# Conference poster landing page

This repository contains a small, mobile-first landing page intended to be linked from a QR code on a conference poster. Visitors can open the poster PDF, find the related publication or repository, and contact the presenting author.

## Edit the page

Open `index.html` and replace every value enclosed in square brackets:

- `[Exact poster title]`
- `[Department / Affiliation]`
- `[Conference, location, year]`
- The research-summary placeholder
- `[PREPRINT_OR_DOI_URL]`
- `[DATA_OR_CODE_URL]`
- `[YOUR_INSTITUTIONAL_EMAIL]`
- `[YOUR_ORCID_URL]` and `[YOUR_ORCID_ID]`
- `[YOUR_LINKEDIN_URL]`

If a resource is unavailable, remove its entire link/button rather than leaving a placeholder live.

## Add the poster

Add the finished PDF to the repository root with the exact filename:

```text
poster.pdf
```

The main button already points to that filename. Keep the PDF reasonably small for phone users; a compressed, screen-readable PDF is usually better than a print-resolution master file.

## Publish with GitHub Pages

1. Open the repository on GitHub.
2. Select **Settings** and then **Pages** in the left sidebar.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then select **Save**.
5. After deployment, GitHub will display the public site URL. It will normally be similar to:

```text
https://ogguli.github.io/conference-poster-links/
```

Use the URL shown in your GitHub Pages settings as the authoritative final address.

## Create the QR code

Create a standard high-contrast QR code that encodes the **landing-page URL**, not the direct PDF URL. The landing page can be updated later without changing the printed QR code.

On the poster, use a clear label such as:

> Poster PDF, research links, and contact — scan here

Before printing:

- Test the live URL and every button.
- Print the QR code at its intended physical size and scan it with at least two phones.
- Prefer a black code on white background with a clear blank margin around it.
- Include an ordinary email address on the poster as a non-QR fallback.
- Use a code around 3 cm wide or larger; make it larger on an A0 poster if people will scan it from arm's length.

## Optional custom domain

GitHub Pages can later use a domain you own. A short address such as `yourdomain.fi/poster` is convenient, but the default GitHub Pages address is fully suitable for a conference poster.
