# VELDORE

Maison de Couture by Sagvan & Ilias — built with Jekyll on GitHub Pages.

## Adding a product

Edit `_data/products.yml`:

```yaml
- name: "Piece Name"
  price: 980.00
  description: "Short description."
  image: "[example.com](https://example.com/image.jpg)"
```

Commit & push — the site rebuilds automatically.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

## Admin password

Edit in `_config.yml` under `admin_password`. Note: this is client-side only and not real security.
