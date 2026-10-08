# TODO — Documentation Yolysi

Registre des points à compléter ou à vérifier. Quand un point est traité, le retirer d'ici **et** remplacer le `TBD` correspondant dans les pages `fr/` et `en/`.

## TBD — Tarifs et montants (à fournir)

- [ ] **Prix des plans** (Gratuit / Starter / Pro / Enterprise) — pages : `credits-et-facturation/plans.md`, `credits-et-facturation/changer-de-plan.md`.
- [ ] **Points mensuels inclus par plan**, nombre de **langues actives** et de **contenus monitorés** par plan (affichés dans l'écran Facturation) — page : `plans.md`.
- [ ] **Coût en points de chaque action** (article optimisé, article via idée, article depuis un produit, fiche produit, evergreen, amélioration par IA, analyse monitoring, audit backlinks, auto-découverte du Brand Kit) — page : `credits-et-facturation/grille-des-couts.md` (les autres pages renvoient vers elle).
- [ ] **Packs de points** : existence, tailles, prix — pages : `comprendre-les-points.md`, `plans.md`.
- [ ] **Tarif du monitoring** : modèle exact (coût par analyse de contenu, quotas par plan) — page : `monitoring/tarif-monitoring.md`.
- [ ] **Coût du MCP / Connexions IA** et règles de facturation côté jetons — page : `integrations-ia/connecter-claude-chatgpt.md`.

## À vérifier avant publication

- [ ] **Écran Facturation protégé par un mot de passe « Beta Tester Access »** dans l'app actuelle : confirmer si ce verrou sera retiré avant la mise en ligne publique ; adapter `credits-et-facturation/*` en conséquence.
- [ ] **Métadonnées SEO à la publication** : le code de publication envoie le titre et le contenu HTML (+ métachamps pour les pages evergreen). Vérifier si la méta-description et les textes alternatifs d'images sont aussi poussés vers Shopify, et le documenter dans `brouillons-et-publication/publier-sur-shopify.md`.
- [ ] **Fiche produit : écrase la description en ligne.** Contrairement aux articles et pages (créés non publiés), la publication d'une fiche produit remplace directement la description du produit. Confirmer que c'est le comportement voulu et s'il faut ajouter une confirmation dans l'app.
- [ ] **Plus d'une langue de contenu** : l'écran de génération propose FR / EN / ES / DE ; confirmer les langues réellement supportées par plan.
- [ ] **Core Web Vitals** : la jauge dépend d'une clé API côté Yolysi ; confirmer qu'elle est active en production avant de promettre cette fonctionnalité.
- [ ] **Délai de purge à la désinstallation** : confirmer la durée annoncée dans `aide/confidentialite-donnees.md`.
- [ ] **Fonctionnalités bêta à valider en conditions réelles** puis retirer le badge `beta: true` : suivi de positions, audit backlinks, Google Ads.
- [ ] **Sorties Vidéo et Podcast** de l'écran de génération : actuellement « Bientôt disponible » — ne pas les documenter comme disponibles.

## Reporté

- [ ] **Utilisation sans Shopify (agences / sites non-Shopify, MCP standalone)** : reportée tant que la boutique d'achat de crédits et la livraison des jetons ne sont pas en place. Page prévue : `integrations-ia/agences-sans-shopify.md`.
- [ ] **Captures d'écran** : 14 emplacements référencés par les pages (mêmes fichiers pour `fr/` et `en/`, idéalement prendre une version par langue d'interface ou en choisir une neutre) :
  - `images/demarrage/01-installation-autorisations.png`, `02-tableau-de-bord.png`
  - `images/brand-kit/01-brand-kit-seo.png`
  - `images/generation/01-choix-type.png`, `02-opportunites-serp.png`
  - `images/brouillons-et-publication/01-liste-brouillons.png`, `02-historique.png`
  - `images/monitoring/01-vue-ensemble.png`, `02-configuration-google.png`, `03-mots-cles-suivis.png`, `04-backlinks.png`
  - `images/credits-et-facturation/01-facturation.png`
  - `images/integrations-ia/01-connexions-ia.png`
  - `images/aide/01-nouveau-ticket.png`
- [ ] **Relecture de la version anglaise** par un anglophone natif.
