# 掘金 - 单个收藏夹

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/collection/:collectionId`
- Route Name: `单个收藏夹`
- Example: `/juejin/collection/6845243180586123271`
- URL: `juejin.cn`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `yang131323`
- Source Location: `collection.ts`
- Source Module: `() => import('@/routes/juejin/collection.ts')`

## Description
_None_

## Parameters
- `collectionId`: 收藏夹唯一标志符, 在浏览器地址栏URL中能够找到


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
  - `juejin.cn/collection/:collectionId`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/juejin/collection/6845243180586123271",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "collection.ts",
  "maintainers": [
    "yang131323"
  ],
  "module": "() => import('@/routes/juejin/collection.ts')",
  "name": "单个收藏夹",
  "parameters": {
    "collectionId": "收藏夹唯一标志符, 在浏览器地址栏URL中能够找到"
  },
  "path": "/collection/:collectionId",
  "radar": [
    {
      "source": [
        "juejin.cn/collection/:collectionId"
      ]
    }
  ]
}
```
