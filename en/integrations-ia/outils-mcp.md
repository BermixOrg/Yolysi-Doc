---
title: Available tools
description: The three tools your AI assistant can call: SERP ideas, blog article, evergreen content.
order: 2
---

# Available tools

Once [connected](connecter-claude-chatgpt.md), your assistant can use three tools. You can request them in natural language.

| Tool | What it does |
|---|---|
| `get_serp_ideas` | Suggests **article ideas** from an analysis of Google results. |
| `generate_blog_article` | Generates a **blog article**, either from an idea returned by `get_serp_ideas` or from a free-form idea. |
| `generate_evergreen` | Generates **evergreen content** (guide, glossary, pillar article). |

## Example flow

1. "Find me article ideas about scented candles for small spaces." → `get_serp_ideas`
2. "Generate article #2." → `generate_blog_article`
3. Open Yolysi → **Drafts**: the article is waiting for your review.

## Good to know

- The result lands as a **draft**: review and [publication](../brouillons-et-publication/publier-sur-shopify.md) happen in Yolysi.
- An article costs the same whether it starts from a SERP idea or a free-form idea.
- Product sheets aren't available through these tools for now.
