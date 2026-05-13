# 成都大学 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `cdu`
- Namespace Name: `成都大学`
- Route Path: `/tzggcdunews`
- Route Name: `通知公告`
- Example: `/cdu/tzggcdunews`
- URL: `news.cdu.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `uuwor`
- Source Location: `tzggcdunews.ts`
- Source Module: `() => import('@/routes/cdu/tzggcdunews.ts')`

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
  - `news.cdu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cdu/tzggcdunews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tzggcdunews.ts",
  "maintainers": [
    "uuwor"
  ],
  "module": "() => import('@/routes/cdu/tzggcdunews.ts')",
  "name": "通知公告",
  "parameters": {},
  "path": "/tzggcdunews",
  "radar": [
    {
      "source": [
        "news.cdu.edu.cn/"
      ]
    }
  ],
  "url": "news.cdu.edu.cn/"
}
```
