---
title: Publish to Shopify
description: Send a draft to a Shopify blog article, page or product sheet, and exactly what happens.
order: 3
---

# Publish to Shopify

## Requirements

A reviewed draft. Once published, content can't be published again (message *This content is already published*).

## Steps

1. On **Drafts** or on the content page, click **Publish to Shopify**.
2. Confirm (*Confirm publishing this content to Shopify?*).
3. For a **blog article**, choose the **destination blog** in the window, then **Publish to this blog**.
4. Wait for it to finish ("Publishing…"). The content moves to **Published**.

## What's created depending on the type

| Content type | What happens in Shopify | Going live |
|---|---|---|
| **Blog article** | An article is created in the chosen blog, with you as author. | **Unpublished**: activate it in Shopify. |
| **Evergreen** | A page is created. Metafields (SEO/AEO scores, schema type, word count…) are added. If the output is an image, it's uploaded to Files. | **Unpublished**: activate it in Shopify. |
| **Product sheet** | The **existing product's description is replaced**. | ⚠️ **Immediate**: the product description changes right away. |

> ⚠️ **Product sheet:** no intermediate step. If the product is live, the new description is live too. Review carefully before confirming.

## After publishing

- For an article or page, open Shopify and set the content to **visible** when you're ready.
- The published content joins the **internal linking** pool: future articles can link to it.
- You can [track it in monitoring](../monitoring/vue-ensemble.md).

## Common errors

| Message | Cause / fix |
|---|---|
| *Session expired, please reload the page* | Reopen the app from the Shopify admin. |
| *Unable to fetch blogs* | Your store may have no blog: create one in Shopify. |
| *Error while publishing* | Retry; if it persists, contact [support](../aide/support.md). |
| Image wasn't processed in time | Shopify processes images with a delay: retry the publication. |
