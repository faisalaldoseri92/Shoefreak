# Shoes Freak BH website

Storefront for Shoes Freak BH (@shoesfreakbh on Instagram): authentic sneakers and trading cards in Bahrain. Customers order by Instagram DM.

## Files
- `index.html` — the whole site
- `img/` — product photos

## Adding or changing items
Edit the `ITEMS` list near the bottom of `index.html` (marked **EDIT HERE**):

```js
{ name: "Nike Total 90 Dynamic Yellow", category: "Sneakers", details: "DM for size & price",
  price: null, status: "available", image: "img/total90.jpg", emoji: "👟", bg: "#ffffff" },
```

- `price: null` shows "Price on DM"
- `status`: `"available"` or `"sold"`
- Put new photos in `img/` and set `image` to their path.

Live preview: https://claude.ai/artifact/Dh3s7xRvZUvZ7K62UMwhu1
