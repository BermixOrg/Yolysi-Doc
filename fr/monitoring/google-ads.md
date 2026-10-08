---
title: Google Ads
description: Voir le Quality Score et la part d'impressions de vos mots-clés Google Ads.
order: 6
beta: true
---

# Google Ads `BÊTA`

> Cette fonctionnalité est en **bêta** : son périmètre est encore en évolution.

## À quoi ça sert

Afficher les performances de vos **mots-clés payants** : coûts, clics, CPC, ROAS, conversions et, avec Google Ads connecté, le **Quality Score officiel** et la **part d'impressions**.

## Deux modes

| Mode | Condition | Ce que vous voyez |
|---|---|---|
| **Google Ads connecté** | Compte Ads choisi dans [Configuration](connecter-google.md) | Quality Score (1 à 10) et part d'impressions officiels. |
| **Estimation** | Pas de compte Ads connecté, mais un compte Ads lié à GA4 | Une colonne **Efficacité**, heuristique interne basée sur taux de conversion et ROAS. **Ce n'est pas le Quality Score de Google.** |

## Connecter un compte Google Ads

1. **Monitoring → Configuration**.
2. Si la carte **Google Ads** affiche *Reconnexion requise*, cliquez sur **Reconnecter Google** pour autoriser l'accès Ads.
3. Dans la liste, **choisissez le compte Google Ads**.

## Lire le tableau

**Mot-clé**, **Clics**, **Coût**, **CPC**, **ROAS**, **Conv.**, puis **Quality Score** et **Part d'impr.** (ou **Efficacité** en mode estimation).

## Si le tableau est vide

*Aucun mot-clé Google Ads sur cette période* : vérifiez que le compte Ads est lié à la propriété GA4 et allongez la période.
