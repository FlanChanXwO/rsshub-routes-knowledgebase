# ShopBack - Store

## Coverage
`index-only`

## Route
- Namespace: `shopback`
- Namespace Name: `ShopBack`
- Route Path: `/:store`
- Route Name: `Store`
- Example: `/shopback/shopee-mart`
- URL: `shopback.com.tw`
- Language: `zh-TW`
- Categories: `shopping`
- Maintainers: `nczitzk`
- Source Location: `store.ts`
- Source Module: `() => import('@/routes/shopback/store.ts')`

## Description
_None_

## Parameters
- `store`: Store, can be found in URL


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
  - `shopback.com.tw/:category`
  - `shopback.com.tw/`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/shopback/shopee-mart",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "store.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/shopback/store.ts')",
  "name": "Store",
  "parameters": {
    "store": "Store, can be found in URL"
  },
  "path": "/:store",
  "radar": [
    {
      "source": [
        "shopback.com.tw/:category",
        "shopback.com.tw/"
      ]
    }
  ]
}
```
