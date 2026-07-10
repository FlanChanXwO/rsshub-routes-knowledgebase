# Gumroad - Products

## Coverage
`index-only`

## Route
- Namespace: `gumroad`
- Namespace Name: `Gumroad`
- Route Path: `/gumroad/:username/:products`
- Route Name: `Products`
- Example: `/gumroad/afkmaster/Eve10`
- URL: `gumroad.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `Fatpandac`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
`https://afkmaster.gumroad.com/l/Eve10` -> `/gumroad/afkmaster/Eve10`

## Parameters
- `username`: username, can be found in URL
- `products`: products name, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "`https://afkmaster.gumroad.com/l/Eve10` -> `/gumroad/afkmaster/Eve10`",
  "example": "/gumroad/afkmaster/Eve10",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "Products",
  "parameters": {
    "products": "products name, can be found in URL",
    "username": "username, can be found in URL"
  },
  "path": "/:username/:products",
  "topFeeds": []
}
```
