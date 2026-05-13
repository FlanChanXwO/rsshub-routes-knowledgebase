# 人人都是产品经理 - 热门文章

## Coverage
`index-only`

## Route
- Namespace: `woshipm`
- Namespace Name: `人人都是产品经理`
- Route Path: `/popular/:range?`
- Route Name: `热门文章`
- Example: `/woshipm/popular`
- URL: `woshipm.com/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `WenryXu`
- Source Location: `popular.ts`
- Source Module: `() => import('@/routes/woshipm/popular.ts')`

## Description
| 日榜  | 周榜   | 月榜    |
| ----- | ------ | ------- |
| daily | weekly | monthly |

## Parameters
- `range`: 时间，见下表，默认为 `daily`


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
  - `woshipm.com/`
- `target`: `/popular`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 日榜  | 周榜   | 月榜    |\n| ----- | ------ | ------- |\n| daily | weekly | monthly |",
  "example": "/woshipm/popular",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "popular.ts",
  "maintainers": [
    "WenryXu"
  ],
  "module": "() => import('@/routes/woshipm/popular.ts')",
  "name": "热门文章",
  "parameters": {
    "range": "时间，见下表，默认为 `daily`"
  },
  "path": "/popular/:range?",
  "radar": [
    {
      "source": [
        "woshipm.com/"
      ],
      "target": "/popular"
    }
  ],
  "url": "woshipm.com/"
}
```
