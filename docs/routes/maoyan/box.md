# 猫眼电影 - 实时票房榜

## Coverage
`index-only`

## Route
- Namespace: `maoyan`
- Namespace Name: `猫眼电影`
- Route Path: `/box`
- Route Name: `实时票房榜`
- Example: `/maoyan/box`
- URL: `maoyan.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `JackyST0`
- Source Location: `box.ts`
- Source Module: `() => import('@/routes/maoyan/box.ts')`

## Description
_None_

## Parameters
_None_


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
  - `piaofang.maoyan.com/dashboard`
- `target`: `/box`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/maoyan/box",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "box.ts",
  "maintainers": [
    "JackyST0"
  ],
  "module": "() => import('@/routes/maoyan/box.ts')",
  "name": "实时票房榜",
  "parameters": {},
  "path": "/box",
  "radar": [
    {
      "source": [
        "piaofang.maoyan.com/dashboard"
      ],
      "target": "/box"
    }
  ]
}
```
