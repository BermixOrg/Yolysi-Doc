---
title: Connecter Google
description: Relier Search Console, Analytics 4 et Google Ads à Yolysi depuis l'onglet Configuration du monitoring.
order: 2
---

# Connecter Google

Une seule connexion Google alimente tout le monitoring. Elle est **facultative**, mais sans elle aucun indicateur de trafic n'est disponible.

## Prérequis

Un compte Google qui a accès à votre propriété Search Console (et, si besoin, à Analytics 4 et Google Ads).

## Étapes

1. Ouvrez **Monitoring → Configuration**.
2. Sous **Connexion Google**, cliquez sur **Connecter Google** et autorisez l'accès. Le badge passe à **Connecté**.
3. **Search Console** *(obligatoire)* : renseignez la propriété, par exemple `sc-domain:maboutique.com` ou `https://www.maboutique.com/`. Vous la trouvez dans Search Console → Propriété → Paramètres.
4. **Analytics 4** *(facultatif)* : choisissez la propriété GA4 liée à la boutique dans la liste.
5. **Google Ads** *(facultatif, bêta)* : choisissez le compte à utiliser, voir [Google Ads](google-ads.md).

![Écran de configuration du monitoring](../../images/monitoring/02-configuration-google.png)

Chaque carte affiche **Configuré** ou **Non configuré**.

## Ce que Yolysi lit

Uniquement des données d'audience et de positionnement (Search Console, Analytics 4, Google Ads). Voir [Confidentialité](../aide/confidentialite-donnees.md).

## Erreurs fréquentes

| Message | Solution |
|---|---|
| *Impossible de charger vos propriétés GA4* | Reconnectez Google et vérifiez que le compte a accès à la propriété. |
| *Aucune propriété GA4 accessible* | Le compte Google connecté n'a pas Analytics 4 : connectez le bon compte. |
| *Propriété connectée mais aucune donnée* | Allongez la période ; une propriété récente peut manquer de données. |
| *Reconnexion requise* (Google Ads) | L'autorisation actuelle ne couvre pas Google Ads : cliquez sur **Reconnecter Google**. |
