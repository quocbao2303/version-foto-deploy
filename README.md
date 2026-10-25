# Version Foto deployment

Verified, prebuilt public website for https://version-foto.de.

Render static site: publish `public`, build command `true`. Existing files are served normally; unknown URLs receive a 301 redirect to `/` through the Render route in `render.yaml`. No standalone 404 page is published.

Source and private working files are maintained separately.
