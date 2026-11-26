# Shoes Freak BH website

Storefront for Shoes Freak BH (@shoesfreakbh on Instagram): authentic sneakers and trading cards in Bahrain. Customers order by Instagram DM.

## Files
- `public/index.html` — the whole site
- `public/img/` — product photos
- `wrangler.jsonc` — Cloudflare settings (site name: shoefreak)

## Adding or changing items
Edit the `ITEMS` list near the bottom of `public/index.html` (marked **EDIT HERE**):

```js
{ name: "Nike Total 90 Dynamic Yellow", category: "Sneakers", details: "DM for size & price",
  price: null, status: "available", image: "img/total90.jpg", emoji: "👟", bg: "#ffffff" },
```

- `price: null` shows "Price on DM"
- `status`: `"available"` or `"sold"`
- Put new photos in `public/img/` and set `image` to their path.

Live preview: https://claude.ai/artifact/Dh3s7xRvZUvZ7K62UMwhu1

Live site (Cloudflare): https://shoefreak.bahrain.workers.dev
