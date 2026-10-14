# ADLeribault Couverture – site vitrine

Site vitrine de SARL ADLeribault Couverture, l'entreprise de couverture d'Adrien et Dylivan Leribault à Saint-Michel-de-Plélan (Côtes-d'Armor).
HTML, CSS et JS natifs : aucune étape de build, aucune dépendance.

Production : https://adleribault-couverture.vercel.app

## Arborescence

```
index.html                     page unique, sprite d'icônes inline, JSON-LD RoofingContractor
assets/css/styles.css          styles, variables de couleur, mode sombre
assets/js/main.js              menu mobile, apparition au défilement, année, formulaire mailto
assets/img/logo.svg            logo horizontal couleur (toit orange, monogramme AD)
assets/img/logo-mono-blanc.svg logo blanc (footer, en-tête en mode sombre)
assets/img/favicon.svg         monogramme carré
robots.txt                     autorise tout, pointe vers le sitemap
sitemap.xml                    une seule URL
```

## Lancer en local

```sh
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000.

## TODO

- Assurance décennale : préciser l'assureur et le contrat (bandeau de réassurance).
- Email : remplacer `leribault.couverture@hotmail.com` par une adresse professionnelle (contact, formulaire, JSON-LD).
- Zone d'intervention : faire confirmer la liste des communes.
- Facebook : ajouter le lien de la page.
- Mentions légales : capital social et numéro RCS.

## Versions

| Version | Date | Direction visuelle |
|---|---|---|
| v1 | 2026-10-14 | Bleu marine et orange du camion, hero centré à motif d'ardoises, prestations en liste numérotée |
