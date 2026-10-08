# Yolysi-Doc

Documentation utilisateur de **Yolysi** (application Shopify SEO / AEO). / End-user documentation for **Yolysi** (Shopify SEO / AEO app).

Tout ce qui est poussé sur `main` est publié automatiquement sur le site de documentation. / Everything pushed to `main` is published automatically on the documentation site.

## Langues / Languages

| Langue | Dossier | Point d'entrée |
|---|---|---|
| Français | [`fr/`](fr/README.md) | [fr/README.md](fr/README.md) |
| English | [`en/`](en/README.md) | [en/README.md](en/README.md) |

## Structure

```
Yolysi-Doc/
├── README.md
├── TODO.md                  # Points à compléter / à vérifier (TBD)
├── images/                  # Captures d'écran partagées par fr/ et en/
├── fr/
│   ├── README.md
│   ├── demarrage/
│   ├── brand-kit/
│   ├── generation/
│   ├── brouillons-et-publication/
│   ├── monitoring/
│   ├── credits-et-facturation/
│   ├── integrations-ia/
│   ├── parametres/
│   └── aide/
└── en/                      # Même arborescence, mêmes noms de fichiers
```

## Conventions de rédaction

- **Mêmes chemins dans `fr/` et `en/`** : une page `fr/x/y.md` a toujours son équivalent `en/x/y.md` (indispensable pour le sélecteur de langue du site).
- **Frontmatter YAML** obligatoire sur chaque page : `title`, `description`, `order` (position dans le menu de la section) ; `beta: true` pour une fonctionnalité en bêta.
- **Plan type d'une page** : à quoi ça sert → prérequis → étapes → coût en points → erreurs fréquentes.
- **Aucun tarif ni montant de points en dur** tant qu'ils ne sont pas arrêtés : écrire `TBD` et référencer l'entrée dans [`TODO.md`](TODO.md).
- **Images** : `images/<section>/NN-slug.png`, référencées en chemin relatif depuis la page (ex. `../../images/generation/01-choix-type.png`). Texte alternatif obligatoire.
- **Noms d'interface** : reprendre exactement les libellés de l'app dans la langue de la page.
