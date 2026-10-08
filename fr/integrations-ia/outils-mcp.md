---
title: Les outils disponibles
description: Les trois outils que votre assistant IA peut appeler : idées SERP, article de blog, contenu evergreen.
order: 2
---

# Les outils disponibles

Une fois [connecté](connecter-claude-chatgpt.md), votre assistant peut utiliser trois outils. Vous pouvez les demander en langage naturel.

| Outil | Ce qu'il fait |
|---|---|
| `get_serp_ideas` | Propose des **idées d'articles** à partir d'une analyse des résultats Google. |
| `generate_blog_article` | Génère un **article de blog**, soit à partir d'une idée issue de `get_serp_ideas`, soit à partir d'une idée libre. |
| `generate_evergreen` | Génère un **contenu evergreen** (guide, glossaire, article pilier). |

## Exemple d'enchaînement

1. « Trouve-moi des idées d'articles sur les bougies parfumées pour petits espaces. » → `get_serp_ideas`
2. « Génère l'article n°2. » → `generate_blog_article`
3. Ouvrez Yolysi → **Brouillons** : l'article vous attend pour relecture.

## À savoir

- Le résultat atterrit en **brouillon** : la relecture et la [publication](../brouillons-et-publication/publier-sur-shopify.md) se font dans Yolysi.
- Le coût d'un article est le même qu'il parte d'une idée SERP ou d'une idée libre.
- Les fiches produits ne sont pas disponibles via ces outils pour l'instant.
