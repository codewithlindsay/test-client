# test-client

Test pushing Shopify themes from phony.

## Dawn-based theme

This repository is a clean, unmodified copy of Shopify's [Dawn](https://github.com/Shopify/dawn) reference theme, committed as the base for the test client. It is intended to be connected to a Shopify dev store via GitHub theme sync.

Standard Shopify Online Store 2.0 theme structure:

- `assets/` — CSS, JS, SVG, and image assets
- `config/` — theme settings (`settings_schema.json`, `settings_data.json`)
- `layout/` — theme layout files (`theme.liquid`, `password.liquid`)
- `locales/` — translation files
- `sections/` — theme sections
- `snippets/` — reusable Liquid snippets
- `templates/` — page templates (JSON + Liquid)

No theme logic has been modified — this is the stock Dawn base. See `release-notes.md` for the Dawn version notes and `LICENSE.md` for licensing.
