# Gadget Flow - Category

## Coverage
`index-only`

## Route
- Namespace: `thegadgetflow`
- Namespace Name: `Gadget Flow`
- Route Path: `/:category?`
- Route Name: `Category`
- Example: `/thegadgetflow/cool-gadgets-gifts`
- URL: `thegadgetflow.com`
- Language: `en`
- Categories: `shopping`
- Maintainers: `EthanWng97`
- Source Location: `rss.tsx`
- Source Module: `() => import('@/routes/thegadgetflow/rss.tsx')`

## Description
_None_

## Parameters
- `category`: category name, can be found in url


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
  - `thegadgetflow.com/categories/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/thegadgetflow/cool-gadgets-gifts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "rss.tsx",
  "maintainers": [
    "EthanWng97"
  ],
  "module": "() => import('@/routes/thegadgetflow/rss.tsx')",
  "name": "Category",
  "parameters": {
    "category": "category name, can be found in url"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "thegadgetflow.com/categories/:category"
      ],
      "target": "/:category"
    }
  ]
}
```
