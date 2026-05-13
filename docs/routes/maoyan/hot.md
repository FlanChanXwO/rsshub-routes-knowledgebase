# 猫眼电影 - 正在热映

## Coverage
`index-only`

## Route
- Namespace: `maoyan`
- Namespace Name: `猫眼电影`
- Route Path: `/hot`
- Route Name: `正在热映`
- Example: `/maoyan/hot`
- URL: `maoyan.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `JackyST0`
- Source Location: `hot.ts`
- Source Module: `() => import('@/routes/maoyan/hot.ts')`

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
  - `www.maoyan.com/films?showType=1`
- `target`: `/hot`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/maoyan/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hot.ts",
  "maintainers": [
    "JackyST0"
  ],
  "module": "() => import('@/routes/maoyan/hot.ts')",
  "name": "正在热映",
  "parameters": {},
  "path": "/hot",
  "radar": [
    {
      "source": [
        "www.maoyan.com/films?showType=1"
      ],
      "target": "/hot"
    }
  ]
}
```
