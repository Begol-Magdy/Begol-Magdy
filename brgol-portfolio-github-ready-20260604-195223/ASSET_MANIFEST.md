# Asset Manifest

## Local Assets

- `public/assets/portrait-bebo.png`: hero portrait supplied by the user.
- `public/assets/project-commerce-flow.png`: generated project cover image.
- `public/assets/project-shopify-store.png`: generated project cover image.
- `public/assets/project-insight-admin.png`: generated project cover image.
- `public/assets/decor/moon-icon.png`: downloaded decorative PNG.
- `public/assets/decor/p59-object.png`: downloaded decorative PNG.
- `public/assets/decor/lego-icon.png`: downloaded decorative PNG.
- `public/assets/decor/group-134.png`: downloaded decorative PNG.
- `public/assets/marquee/hero-space-voyage.gif`: downloaded marquee GIF.
- `src/assets/fonts/kanit.css` and `src/assets/fonts/kanit-*.woff2`: self-hosted Kanit font files.

## Marquee Note

The original website referenced 21 remote MotionSites GIF URLs. During packaging, only `hero-space-voyage-preview-eECLH3Yc.gif` could be downloaded successfully because the MotionSites host repeatedly timed out for the remaining files from this environment.

To make the GitHub package self-contained and avoid broken external image dependencies, the marquee now uses local assets only: the downloaded GIF plus local project cover images.

## Intentional External Links

These are outbound links, not downloaded assets:

- `mailto:begol.m.ayoub@gmail.com`
- `https://wa.me/201204203545`
- Placeholder project links under `https://example.com/...`

Replace the placeholder project links in `src/App.tsx` when real project deployments are available.
