# Plantilla IPOP (1DAM / 2DAM)

Plantilla en HTML i CSS per construir el teu Portafoli IPOP (Informe Personal
per l'Orientació Professional) i publicar-lo amb GitHub Pages.

## Fitxers

- `index.html` — Perfil i Projecció Professional (pàgina d'inici)
- `autoconeixement.html` — Autoconeixement (DAFO personal, interessos, valors)
- `mercat-professional.html` — Coneixement del Mercat
- `pla-accio.html` — Pla d'Acció
- `style.css` — estils compartits per les 4 pàgines
- `cv.pdf` — (opcional) el teu CV, si vols enllaçar-lo des de `index.html`

## Com personalitzar-la

1. Obre cada fitxer `.html` i substitueix tot el text entre claudàtors, per
   exemple `[El teu Nom i Cognoms]`, pel teu contingut real.
2. El teu nom i el nom del centre apareixen a la capçalera de cada pàgina:
   busca'ls i canvia'ls a les 4 pàgines.
3. Pots afegir o treure seccions (blocs `<div class="card">`) segons el que
   et demani el/la tutor/a.
4. Si vols canviar el color d'una secció, edita la variable `--accent` a
   `style.css` (una per pàgina: `--accent-perfil`, `--accent-auto`,
   `--accent-mercat`, `--accent-pla`).

## Com publicar-ho a GitHub Pages

1. Crea un repositori nou a GitHub (per exemple `ipop-nom-cognom`).
2. Puja aquests fitxers al repositori (mantenint tots al mateix nivell, no
   dins d'una subcarpeta).
3. Ves a **Settings → Pages**, i a "Branch" selecciona `main` i la carpeta
   `/ (root)`. Desa els canvis.
4. Al cap d'uns minuts, la teva web estarà disponible a:
   `https://el-teu-usuari.github.io/ipop-nom-cognom/`
5. Comparteix aquest enllaç amb el/la professor/a per a la revisió.
