# 南昌大学 - 教务通知

## Coverage
`index-only`

## Route
- Namespace: `ncu`
- Namespace Name: `南昌大学`
- Route Path: `/jwc`
- Route Name: `教务通知`
- Example: `/ncu/jwc`
- URL: `jwc.ncu.edu.cn/Notices.jsp`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ywh555hhh, jixiuweilan`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/ncu/jwc.ts')`

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
  - `jwc.ncu.edu.cn`
- `target`: `/jwc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/ncu/jwc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "ywh555hhh",
    "jixiuweilan"
  ],
  "module": "() => import('@/routes/ncu/jwc.ts')",
  "name": "教务通知",
  "parameters": {},
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.ncu.edu.cn"
      ],
      "target": "/jwc"
    }
  ],
  "url": "jwc.ncu.edu.cn/Notices.jsp"
}
```
