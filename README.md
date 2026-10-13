# Sri Padmavathi Construction — Final Website

This package has been arranged for static hosting and custom-domain deployment.

## Fixed
- Replaced the old One Window logo with the supplied Sri Padmavathi Construction logo.
- Removed the broken hero image reference and reused an included project image.
- Kept all project images inside the `images/` folder with matching relative paths.
- `index.html`, `styles.css`, `script.js`, and `images/` are at the same project root level.

## Deployment
Upload the contents of this folder as the website root. Do not upload only `index.html`; the entire `images` folder must be deployed with it.

For Vite/React hosting, use the production build output (`dist`) and make sure the configured base path matches the deployment path.
