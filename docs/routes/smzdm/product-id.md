# 什么值得买 - 商品

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/product/:id`
- Route Name: `商品`
- Example: `/smzdm/product/zm5vzpe`
- URL: `post.smzdm.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `chesha1`
- Source Location: `product.ts`
- Source Module: `() => import('@/routes/smzdm/product.ts')`

## Description
_None_

## Parameters
- `id`: 商品 id，网址上直接可以看到


## Features
- `requireConfig`: [{"description": "什么值得买登录后的 Cookie 值", "name": "SMZDM_COOKIE"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `wiki.smzdm.com/p/:id`
- `target`: `/product/:id`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/smzdm/product/zm5vzpe",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "什么值得买登录后的 Cookie 值",
        "name": "SMZDM_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "product.ts",
  "maintainers": [
    "chesha1"
  ],
  "module": "() => import('@/routes/smzdm/product.ts')",
  "name": "商品",
  "parameters": {
    "id": "商品 id，网址上直接可以看到"
  },
  "path": "/product/:id",
  "radar": [
    {
      "source": [
        "wiki.smzdm.com/p/:id"
      ],
      "target": "/product/:id"
    }
  ]
}
```
