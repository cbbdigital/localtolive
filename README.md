# Ciprian Badic — Fotografie de arhitectură & real estate

Site static (un singur `index.html`) cu galerie pe proiecte. Pozele sunt optimizate pentru web (max 2000px, JPEG).

## Publicare pe GitHub Pages
1. Creează un repo nou (ex. `portfolio`) și urcă tot conținutul acestui folder.
2. Settings → Pages → Source: `Deploy from a branch` → branch `main`, folder `/root`.
3. Site-ul va fi live la `https://<user>.github.io/portfolio/`.

## Structură
- `index.html` — pagina
- foldere cu poze (HIGHLIGHT, Proiect 1..., Rent Appartment..., personal)

## Cum adaugi/schimbi poze
Editează listele din `<script>` în `index.html`:
- `HERO` — pozele din slideshow-ul de pe prima pagină
- `projects[...]` — fiecare proiect are `photos:[...]` în ordinea dorită
