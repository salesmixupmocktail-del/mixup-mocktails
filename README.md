# Mix Up Mocktails website

Storefront for Mix Up Mocktails: six mocktail mixers, a cart that hands off to Shopify checkout, pre-orders and a feedback form.

## Folders

- `docs/` is the published website (GitHub Pages serves this folder). `docs/CNAME` sets the domain to www.mixupmocktails.in.
- `index.html` and `assets/` are the source of the Claude preview page.

## Editing

Products, prices and photos are set in the `PRODUCTS` list near the bottom of `index.html`. Shopify variant IDs are in `SHOPIFY_VARIANTS`.

After changing `index.html`, copy it into `docs/index.html` (wrapped in the `<!doctype html>` head that file already has), then commit and push.

## Publishing on GitHub Pages

Repository Settings → Pages → Deploy from a branch → `main` / `docs`.
