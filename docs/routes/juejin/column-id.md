# 掘金 - 专栏

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/column/:id`
- Route Name: `专栏`
- Example: `/juejin/column/6960559453037199391`
- URL: `juejin.cn`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `xiangzy1`
- Source Location: `column.ts`
- Source Module: `() => import('@/routes/juejin/column.ts')`

## Description
_None_

## Parameters
- `id`: 专栏 id, 可在专栏页 URL 中找到


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
  - `juejin.cn/column/:id`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/juejin/column/6960559453037199391",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "column.ts",
  "maintainers": [
    "xiangzy1"
  ],
  "module": "() => import('@/routes/juejin/column.ts')",
  "name": "专栏",
  "parameters": {
    "id": "专栏 id, 可在专栏页 URL 中找到"
  },
  "path": "/column/:id",
  "radar": [
    {
      "source": [
        "juejin.cn/column/:id"
      ]
    }
  ]
}
```
