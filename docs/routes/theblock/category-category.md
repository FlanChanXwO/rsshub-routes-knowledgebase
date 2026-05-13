# TheBlock - Category

## Coverage
`index-only`

## Route
- Namespace: `theblock`
- Namespace Name: `TheBlock`
- Route Path: `/category/:category`
- Route Name: `Category`
- Example: `/theblock/category/crypto-ecosystems`
- URL: `theblock.co`
- Language: `en`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/theblock/index.ts')`

## Description
Get latest news from TheBlock by category. Note that due to website limitations, only article summaries may be available.

## Parameters
- `category`: News category


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
  - `theblock.co/category/:category`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Get latest news from TheBlock by category. Note that due to website limitations, only article summaries may be available.",
  "example": "/theblock/category/crypto-ecosystems",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "module": "() => import('@/routes/theblock/index.ts')",
  "name": "Category",
  "parameters": {
    "category": "News category"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "theblock.co/category/:category"
      ],
      "target": "/category/:category"
    }
  ]
}
```
