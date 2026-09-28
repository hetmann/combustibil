# Combustibil

Public information, privacy, terms, support and data deletion pages in Romanian and English.

Hosted with GitHub Pages at https://combustibil.hetmann.dev.

## Landing page

Original static implementation inspired by the public Pocket layout, adapted to Combustibil. No paid template source is bundled. The phone is an illustrative mockup with sample data.

Edit bilingual copy in `scripts/build-home.py`, then run `python3 scripts/build-home.py`. Store links are configured in `stores.json`: replace null only with a verified public App Store/TestFlight or Google Play URL, then regenerate. Null renders an explicitly disabled Coming soon button.

Legal documents remain separate at `/ro/` and `/en/`. No JavaScript, analytics, or external fonts are loaded.
