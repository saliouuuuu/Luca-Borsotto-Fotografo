# Luca Borsotto Fotografo — sito portfolio

Sito one-page in un solo file (`index.html`): HTML, CSS e JS, senza librerie e senza build.
Le foto stanno in `img/`.

## Prima di pubblicare

1. **Contatti** — in fondo a `index.html` c'è il blocco `CONFIG`: inserisci numero WhatsApp
   (formato `39` + numero, solo cifre), telefono, email, Instagram e P.IVA (obbligatoria per legge).
2. **Foto in alta risoluzione** — i file attuali sono miniature (179 px di larghezza).
   Sostituiscili con gli originali esportati a circa 2000–2400 px sul lato lungo,
   JPEG qualità 80 (~300–500 KB ciascuno), **mantenendo gli stessi nomi file**.
   Poi aggiorna `width`/`height` dei tag `<img>` (servono solo per le proporzioni).
3. **Dominio** — aggiorna `canonical` e `og:image` nell'`<head>` con l'URL definitivo.

## Aggiungere una foto al portfolio

Copia un blocco `<figure class="shot">` dentro `#grid` e cambia:
`src`, `alt`, `data-cat` (una o più tra `matrimoni coppie ritratti famiglia paesaggi`),
`data-exif` e il testo dei dati EXIF nell'overlay.

## Pubblicazione

Qualsiasi hosting statico: GitHub Pages, Netlify, Cloudflare Pages. Basta caricare `index.html` e `img/`.
