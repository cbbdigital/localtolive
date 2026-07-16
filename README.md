# Local to Live

Landing page pentru **Local to Live** (CBB DIGITAL SRL) — program de 90 de zile de social media & marketing digital pentru afaceri locale.

Pagină single-file: tot HTML/CSS/JS este inline în `index.html`, fără dependențe de build. Singura resursă externă este fontul Space Grotesk de la Google Fonts.

## Structură

```
index.html      # pagina completă
README.md
```

## Rulare locală

Deschide `index.html` direct în browser, sau pornește un server static:

```bash
python3 -m http.server 8000
# apoi deschide http://localhost:8000
```

## Publicare pe GitHub Pages

1. Creează un repo nou pe GitHub și urcă fișierele:

   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<user>/<repo>.git
   git push -u origin main
   ```

2. În repo → **Settings → Pages** → Source: `Deploy from a branch` → Branch: `main` / `root`.
3. Site-ul va fi disponibil la `https://<user>.github.io/<repo>/`.

## Caracteristici

- Entry animation: dreptunghi vertical cu grafică stil video (nu video), zoom-in la intrare
- Hero desktop pe două coloane (card + text lateral), stivuit pe mobil
- Secțiune servicii cu carduri interactive și mockup-uri animate
- Secțiune exclusivitate cu feed stil TikTok
- Formular de înscriere (mailto) și footer conform ANPC / GDPR

## Tehnologii

HTML, CSS și JavaScript vanilla. Fără framework, fără pas de build.
