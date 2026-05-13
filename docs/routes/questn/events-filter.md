# QuestN - Events

## Coverage
`index-only`

## Route
- Namespace: `questn`
- Namespace Name: `QuestN`
- Route Path: `/events/:filter?`
- Route Name: `Events`
- Example: `/questn/events`
- URL: `app.questn.com`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `cxheng315`
- Source Location: `events.ts`
- Source Module: `() => import('@/routes/questn/events.ts')`

## Description
::: tip

Filter parameters:
- category: 100: trending, 200: newest, 300: top
- status_filter: 0: all, 100: available, 400: missed
- community_filter: 0: all community, 100: verified, 200: followed
- rewards_filter: 0: all rewards, 100: nft, 200: token, 400: whitelist
- chain_filter: 0: all chains, 1: ethereum, 56: bsc, 137: polygon, 42161: arb, 10: op, 324: zksync, 43114: avax
- search: 'Search keyword',
- count: 'Number of events to fetch',
- page: 'Page number',
:::

## Parameters
- `filter`: Filter string


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `app.questn.com/explore`
- `target`: `/events/:category?/:status_filter?/:community_filter?/:reward_filter?/:chain_filter?/:search?/:count?/:page?`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "\n::: tip\n\nFilter parameters:\n- category: 100: trending, 200: newest, 300: top\n- status_filter: 0: all, 100: available, 400: missed\n- community_filter: 0: all community, 100: verified, 200: followed\n- rewards_filter: 0: all rewards, 100: nft, 200: token, 400: whitelist\n- chain_filter: 0: all chains, 1: ethereum, 56: bsc, 137: polygon, 42161: arb, 10: op, 324: zksync, 43114: avax\n- search: 'Search keyword',\n- count: 'Number of events to fetch',\n- page: 'Page number',\n:::",
  "example": "/questn/events",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "events.ts",
  "maintainers": [
    "cxheng315"
  ],
  "module": "() => import('@/routes/questn/events.ts')",
  "name": "Events",
  "parameters": {
    "filter": "Filter string"
  },
  "path": "/events/:filter?",
  "radar": [
    {
      "source": [
        "app.questn.com/explore"
      ],
      "target": "/events/:category?/:status_filter?/:community_filter?/:reward_filter?/:chain_filter?/:search?/:count?/:page?"
    }
  ],
  "url": "app.questn.com"
}
```
