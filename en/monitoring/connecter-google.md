---
title: Connect Google
description: Link Search Console, Analytics 4 and Google Ads to Yolysi from the monitoring Setup tab.
order: 2
---

# Connect Google

A single Google connection feeds all of monitoring. It's **optional**, but without it no traffic indicator is available.

## Requirements

A Google account with access to your Search Console property (and, if needed, Analytics 4 and Google Ads).

## Steps

1. Open **Monitoring → Setup**.
2. Under **Google connection**, click **Connect Google** and grant access. The badge turns **Connected**.
3. **Search Console** *(required)*: enter the property, for example `sc-domain:mystore.com` or `https://www.mystore.com/`. You'll find it in Search Console → Property → Settings.
4. **Analytics 4** *(optional)*: choose the GA4 property linked to the store from the list.
5. **Google Ads** *(optional, beta)*: choose the account to use, see [Google Ads](google-ads.md).

![Monitoring setup screen](../../images/monitoring/02-configuration-google.png)

Each card shows **Configured** or **Not configured**.

## What Yolysi reads

Only audience and ranking data (Search Console, Analytics 4, Google Ads). See [Privacy](../aide/confidentialite-donnees.md).

## Common errors

| Message | Fix |
|---|---|
| *Could not load your GA4 properties* | Reconnect Google and check the account can access the property. |
| *No GA4 property accessible* | The connected Google account has no Analytics 4: connect the right account. |
| *Property connected but no data* | Use a longer period; a recent property may lack data. |
| *Reconnect required* (Google Ads) | The current authorization doesn't cover Google Ads: click **Reconnect Google**. |
