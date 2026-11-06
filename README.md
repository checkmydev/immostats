# ImmoStats — Observatoire de l'immobilier belge

Dashboard interactif des prix de l'immobilier en Belgique, construit sur les données
ouvertes de **Statbel** (SPF Finances), du S1 2010 au S1 2026.

**En ligne :** https://checkmydev.github.io/immostats/

## Contenu

- Prix médians (maisons / appartements) par région, province et commune
- Volumes de transactions, évolution annuelle
- Indice des prix des logements (HPI) trimestriel
- 565 communes couvertes

## Source des données

- [Prix de l'immobilier — Statbel](https://statbel.fgov.be/fr/themes/construction-logement/prix-de-limmobilier)
- [Indice des prix des logements — Statbel](https://statbel.fgov.be/fr/themes/construction-logement/indice-des-prix-des-logements)
- [Ventes immobilières sur le marché secondaire — Statbel](https://statbel.fgov.be/fr/themes/construction-logement/ventes-immobilieres-sur-le-marche-secondaire)

Licence des données : **CC BY 4.0**.

## Technique

`index.html` est un fichier autonome : CSS, données et code sont embarqués.
Aucune dépendance, aucun appel réseau — il suffit de l'ouvrir dans un navigateur.

Hébergé via GitHub Pages (branche `main`, racine).
