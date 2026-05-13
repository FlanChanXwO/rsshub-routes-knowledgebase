# 掘金 - 收藏集

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/collections/:userId`
- Route Name: `收藏集`
- Example: `/juejin/collections/1697301682482439`
- URL: `juejin.cn`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `yang131323`
- Source Location: `collections.ts`
- Source Module: `() => import('@/routes/juejin/collections.ts')`

## Description
_None_

## Parameters
- `userId`: 用户唯一标志符, 在浏览器地址栏URL中能够找到


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
  - `juejin.cn/user/:id`
  - `juejin.cn/user/:id/collections`
- `target`: `/collections/:id`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/juejin/collections/1697301682482439",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "collections.ts",
  "maintainers": [
    "yang131323"
  ],
  "module": "() => import('@/routes/juejin/collections.ts')",
  "name": "收藏集",
  "parameters": {
    "userId": "用户唯一标志符, 在浏览器地址栏URL中能够找到"
  },
  "path": "/collections/:userId",
  "radar": [
    {
      "source": [
        "juejin.cn/user/:id",
        "juejin.cn/user/:id/collections"
      ],
      "target": "/collections/:id"
    }
  ]
}
```
