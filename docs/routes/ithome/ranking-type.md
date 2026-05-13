# iThome 台灣 - 热榜

## Coverage
`index-only`

## Route
- Namespace: `ithome`
- Namespace Name: `iThome 台灣`
- Route Path: `/ranking/:type`
- Route Name: `热榜`
- Example: `/ithome/ranking/24h`
- URL: `ithome.com`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `immmortal, luyuhuang`
- Source Location: `ranking.ts`
- Source Module: `() => import('@/routes/ithome/ranking.ts')`

## Description
| 24h           | 7days    | monthly |
| ------------- | -------- | ------- |
| 24 小时阅读榜 | 7 天最热 | 月榜    |

## Parameters
- `type`: 类别


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
    "new-media"
  ],
  "description": "| 24h           | 7days    | monthly |\n| ------------- | -------- | ------- |\n| 24 小时阅读榜 | 7 天最热 | 月榜    |",
  "example": "/ithome/ranking/24h",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ranking.ts",
  "maintainers": [
    "immmortal",
    "luyuhuang"
  ],
  "module": "() => import('@/routes/ithome/ranking.ts')",
  "name": "热榜",
  "parameters": {
    "type": "类别"
  },
  "path": "/ranking/:type"
}
```
