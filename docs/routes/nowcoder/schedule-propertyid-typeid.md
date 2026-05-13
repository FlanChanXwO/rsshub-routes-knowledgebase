# 牛客网 - 校招日程

## Coverage
`index-only`

## Route
- Namespace: `nowcoder`
- Namespace Name: `牛客网`
- Route Path: `/schedule/:propertyId?/:typeId?`
- Route Name: `校招日程`
- Example: `/nowcoder/schedule`
- URL: `nowcoder.com/`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `junfengP`
- Source Location: `schedule.ts`
- Source Module: `() => import('@/routes/nowcoder/schedule.ts')`

## Description
_None_

## Parameters
- `propertyId`: 行业, 在控制台中抓取接口，可获得行业id，默认0
- `typeId`: 类别，同上


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
  - `nowcoder.com/`
- `target`: `/schedule`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/nowcoder/schedule",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "schedule.ts",
  "maintainers": [
    "junfengP"
  ],
  "module": "() => import('@/routes/nowcoder/schedule.ts')",
  "name": "校招日程",
  "parameters": {
    "propertyId": "行业, 在控制台中抓取接口，可获得行业id，默认0",
    "typeId": "类别，同上"
  },
  "path": "/schedule/:propertyId?/:typeId?",
  "radar": [
    {
      "source": [
        "nowcoder.com/"
      ],
      "target": "/schedule"
    }
  ],
  "url": "nowcoder.com/"
}
```
