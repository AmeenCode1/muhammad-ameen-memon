# Muhammad Ameen Memon — Personal Website

A complete static personal-brand website for Muhammad Ameen Memon, a Real Estate Virtual Assistant & Digital Marketing Specialist. It uses plain HTML5 and CSS3, with no JavaScript, framework, package manager, backend, build step, paid template, or external runtime dependency.

## Live site and repository

- **Website:** https://ameencode1.github.io/muhammad-ameen-memon/
- **GitHub repository:** https://github.com/AmeenCode1/muhammad-ameen-memon
- **Pages source:** the `main` branch, repository root.

## Project files

- `index.html` — the homepage and all page sections, SEO metadata, canonical URL, and social-sharing metadata.
- `style.css` — responsive layout, colors, typography, components, and the CSS-only hero illustration.
- `assets/social-preview.png` — local 1200 × 630 Open Graph/Twitter preview image.
- `robots.txt` — crawler access and sitemap location.
- `sitemap.xml` — one-page sitemap using the published URL.
- `manus-routes.json` — local preview route declaration; not required by GitHub Pages.

The hero visual is drawn with CSS, so the site has no external or unverified image dependency. The social preview image is stored locally. Local asset paths are relative, so the site works from this GitHub Pages project URL and does not need server-side routing or a build step.

## Update and republish

To change the site, edit the files in this folder or in the repository. Keep the homepage at the repository root as `index.html`. Commit and push changes to `main`; GitHub Pages serves the branch root. No build command or GitHub Actions workflow is required.

If the repository name, GitHub username, or custom domain changes, update all absolute origin values in the canonical link, `og:url`, social-sharing image URLs, `robots.txt`, and `sitemap.xml`. The canonical homepage is currently `https://ameencode1.github.io/muhammad-ameen-memon/`; the sitemap is `https://ameencode1.github.io/muhammad-ameen-memon/sitemap.xml`.

### Personal details and content

- **Email:** Search `ameen.realtorva@gmail.com` in `index.html` and replace all visible and `mailto:` instances if the contact email changes.
- **LinkedIn:** A disabled button is shown because no real profile URL was supplied. The `data-placeholder-url` value and nearby HTML comment use `https://www.linkedin.com/in/YOUR-PROFILE` as a clearly non-working placeholder. Replace it with your real profile URL and convert the disabled control to a normal link only when ready.
- **Hero/profile image:** The current hero is a CSS illustration. The comment marked `PROFILE IMAGE` in `index.html` shows where to replace it with an approved local image and descriptive alt text. If you add a local image, put it in an `assets/` folder and use a relative path.
- **Portfolio:** Search for `PORTFOLIO ITEMS` in `index.html`. Replace the six marked placeholder descriptions/visuals only with work samples you have permission to share. Do not include client data or unsupported results.
- **Contact form:** The form is a visual preview and intentionally cannot submit. To collect form submissions, connect an approved form provider, add its documented endpoint and any required protections, test it, then enable the submit control and revise the notice. Until then, the email link is the working contact method.
- **Copyright year:** Update `© 2026` in the footer when needed.

## Google Search Console

1. Open [Google Search Console](https://search.google.com/search-console/) and add a **URL-prefix** property using `https://ameencode1.github.io/muhammad-ameen-memon/`.
2. Select an ownership-verification method. For the HTML-tag method, add the supplied verification meta tag inside the `<head>` of `index.html`, publish the change to `main`, then select **Verify**. For the HTML-file method, add Google's exact verification file to the repository root and publish it at the URL Search Console specifies.
3. In Search Console, open **Sitemaps** and submit `https://ameencode1.github.io/muhammad-ameen-memon/sitemap.xml`.
4. Check the Pages and URL inspection reports over time. Sitemap submission does not guarantee indexing or a particular search position.
