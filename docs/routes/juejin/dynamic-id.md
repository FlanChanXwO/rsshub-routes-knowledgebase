# 掘金 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/dynamic/:id`
- Route Name: `用户动态`
- Example: `/juejin/dynamic/3051900006845944`
- URL: `juejin.cn`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `CaoMeiYouRen`
- Source Location: `dynamic.ts`
- Source Module: `() => import('@/routes/juejin/dynamic.ts')`

## Description
_None_

## Parameters
- `id`: 用户 id, 可在用户页 URL 中找到


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

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/juejin/dynamic/3051900006845944",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dynamic.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/juejin/dynamic.ts')",
  "name": "用户动态",
  "parameters": {
    "id": "用户 id, 可在用户页 URL 中找到"
  },
  "path": "/dynamic/:id",
  "radar": [
    {
      "source": [
        "juejin.cn/user/:id"
      ]
    }
  ]
}
```
