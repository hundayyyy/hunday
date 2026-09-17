# Betemaryam Birthday Website

## Deployment
Upload the contents of this ZIP to the GitHub repository connected to Netlify. Keep `content.json` and the `media/` folder at the project root.

## Admin Panel
Open `/admin/`. Decap CMS uses Git Gateway and saves media to `media/`, published as `/media/`.

## Important
Enable Netlify Identity and Git Gateway for the Netlify site. After publishing an edit, confirm the change appears in `content.json` on the `main` branch.

The public page fetches `/content.json` with cache-busting and has a built-in fallback so the page still renders if the JSON request temporarily fails.
