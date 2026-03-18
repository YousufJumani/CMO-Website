# Elara Voss - Fractional CMO Portfolio Landing Page

A bold, editorial-style personal brand website for a fictional Fractional CMO profile.

This project is a highly art-directed single-page site built with semantic HTML, Tailwind (CDN), custom CSS, and lightweight JavaScript interactions.

## Design Highlights

- Asymmetric editorial layout with intentional anti-grid composition
- Custom typography pairing (Cormorant Garamond + DM Sans)
- Animated organic background blobs and marquee strip
- Expand-on-hover service cards
- Scroll reveal animations and custom cursor interaction
- Strong section storytelling: Services, Work, About, Contact

## Tech Stack

- HTML5
- Tailwind CSS (CDN)
- Custom CSS animations
- Vanilla JavaScript (DOM interactions and reveals)

## Project Structure

```text
project2 - cmo/
  index.html
```

## Run Locally

Because this is a static site, you can run it in multiple ways.

### Option A: Open directly

Open `index.html` in your browser.

### Option B: Run a static local server (recommended)

```bash
npx serve -l 4174 .
```

Then open:

- `http://localhost:4174`

## Verified Run Status

Validated on March 18, 2026:

- Local static server launched successfully
- Homepage returned `200 OK` on local request

## Deployment on Vercel

If this project is pushed as its own repository:

1. Import the repository in Vercel.
2. Framework preset: `Other`.
3. Build command: leave empty.
4. Output directory: leave empty (or `.`).
5. Deploy.

If this project is inside a monorepo/workspace:

1. Import the repository in Vercel.
2. Set Root Directory to `project2 - cmo`.
3. Keep build settings empty.
4. Deploy.

## Portfolio Notes

To make this even stronger for GitHub and Vercel showcase:

- Add Open Graph meta tags for social sharing
- Add a favicon to remove 404 requests for `/favicon.ico`
- Add one or two real case studies with outbound links

## License

For portfolio and educational use.
