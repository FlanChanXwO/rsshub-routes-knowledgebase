# 猫眼电影 - 即将上映

## Coverage
`index-only`

## Route
- Namespace: `maoyan`
- Namespace Name: `猫眼电影`
- Route Path: `/coming`
- Route Name: `即将上映`
- Example: `/maoyan/coming`
- URL: `maoyan.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `JackyST0`
- Source Location: `coming.ts`
- Source Module: `() => import('@/routes/maoyan/coming.ts')`

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
  - `www.maoyan.com/films?showType=2`
  - `www.maoyan.com/films`
- `target`: `/coming`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/maoyan/coming",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "coming.ts",
  "maintainers": [
    "JackyST0"
  ],
  "module": "() => import('@/routes/maoyan/coming.ts')",
  "name": "即将上映",
  "parameters": {},
  "path": "/coming",
  "radar": [
    {
      "source": [
        "www.maoyan.com/films?showType=2",
        "www.maoyan.com/films"
      ],
      "target": "/coming"
    }
  ]
}
```
