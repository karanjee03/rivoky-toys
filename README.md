# RIVOKI Toys — V3

This is the refreshed single-page RIVOKI toy-shop concept.

## What changed in V3
- Replaced the original mixed retailer/CDN photo URLs with direct Unsplash CDN photo links for the main categories and product photography.
- Added a second real-photo URL for each image wherever practical.
- Added an image error handler: if the primary image fails, it tries its backup; if both fail, it removes the broken-image icon and shows a designed branded placeholder rather than a blank/broken image.
- Preserved the existing light/dark theme toggle, circular View Transition animation, category filters, search, wishlist, cart drawer, and responsive layout.
- Added links to selected Unsplash source pages in the footer photo credits.

## Open locally
Keep `index.html` as-is and open it in Chrome. An internet connection is required for the remote photographs and Google Fonts.

## Publish
Upload the extracted `rivoki-toys-v3` folder to a static host such as Netlify Drop. The HTML is self-contained; there are no separate CSS or JavaScript build steps.

## Important project notes
- Product names and PKR prices are illustrative/demo content.
- The cart and checkout are front-end demonstrations only. No payment, stock, delivery, email or order backend is connected.
- The Unsplash photos are mood/product-category demonstration images, not verified photographs of the exact demo SKUs. Replace them with images supplied by the actual toy vendors before using the store commercially, and retain the image credits/licence records.
