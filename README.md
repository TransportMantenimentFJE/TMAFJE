# TMA — Escola del Clot (GitHub Pages + Reveal.js)

Aquest repositori conté una presentació web estàtica (tipus "PowerPoint") basada en **Reveal.js** i publicada amb **GitHub Pages**.

## Com publicar
1. Puja el contingut d’aquest repositori al teu GitHub (`ignasi-pujol/tma-site`).
2. Vés a **Settings → Pages** i estableix **Source = Branch `main`** (arrel). Un cop guardat, GitHub Pages generarà l’URL pública del projecte.
3. (Opcional) Domini personalitzat: a **Settings → Pages → Custom domain** escriu `tma.clot.cat`. Al DNS del domini crea un **CNAME** per `tma` apuntant a `ignasi-pujol.github.io`. Activa **Enforce HTTPS**.

> Docs GitHub Pages: publicació i domini personalitzat.

## Editar contingut
- Obre `index.html` i edita cada `<section>` (cada secció és una diapositiva).
- Canvia el **tema** de Reveal canviant la línia del CSS `dist/theme/black.css` per `white.css`, `league.css`, etc.
- Pots afegir imatges a `assets/img/` i inserir-les amb `<img src="assets/img/nom.jpg" alt="...">`.

## Licència
Ús intern/educatiu.
