# De Korenaar – GitHub Pages

Deze repo is klaar voor GitHub Pages (Jekyll staat aan, maar de site is gewoon een `index.html`).

## Deploy (via GitHub UI)

1. Maak een nieuwe repository (bijv. `korenaar-pages`)
2. Upload de bestanden uit deze zip naar de root van de repo
3. Ga naar **Settings → Pages**
4. Bij **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main` (of `master`) / folder: `/ (root)`
5. Wacht tot GitHub Pages klaar is en open de gegeven URL

## Lokaal testen (optioneel)

- Open `index.html` direct in je browser
- Of draai Jekyll lokaal:
  - `bundle exec jekyll serve`
