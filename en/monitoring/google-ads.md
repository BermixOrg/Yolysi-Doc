---
title: Google Ads
description: See the Quality Score and impression share of your Google Ads keywords.
order: 6
beta: true
---

# Google Ads `BETA`

> This feature is in **beta**: its scope is still evolving.

## What it's for

Show the performance of your **paid keywords**: costs, clicks, CPC, ROAS, conversions and, with Google Ads connected, the **official Quality Score** and **impression share**.

## Two modes

| Mode | Condition | What you see |
|---|---|---|
| **Google Ads connected** | Ads account chosen in [Setup](connecter-google.md) | Official Quality Score (1 to 10) and impression share. |
| **Estimate** | No Ads account connected, but an Ads account linked to GA4 | An **Efficiency** column, an in-house heuristic based on conversion rate and ROAS. **This is not Google's Quality Score.** |

## Connect a Google Ads account

1. **Monitoring → Setup**.
2. If the **Google Ads** card shows *Reconnect required*, click **Reconnect Google** to grant Ads access.
3. In the list, **choose the Google Ads account**.

## Reading the table

**Keyword**, **Clicks**, **Cost**, **CPC**, **ROAS**, **Conv.**, then **Quality Score** and **Impr. share** (or **Efficiency** in estimate mode).

## If the table is empty

*No Google Ads keywords for this period*: check that the Ads account is linked to the GA4 property and use a longer period.
