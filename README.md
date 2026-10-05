# Global Holy Rosary

Pray the Rosary for every nation in its own language, and watch the world map turn gold.

- `index.html` is the whole app.
- `data/countries.json` holds 197 nations: Catholic history, saints, cathedrals and prayer intentions.
- `data/languages.json` holds the Rosary prayers in 104 languages. Each language has a `status`: `established`, `verify` or `partial`.
- `data/map.json` is the world map, already drawn as SVG paths.

Accounts and Rosary counts are stored in the app's Supabase database.

## Correcting a translation
1. Open `data/languages.json` on GitHub and click the pencil icon.
2. Edit the text.
3. Commit the change.

The site updates within a minute.
