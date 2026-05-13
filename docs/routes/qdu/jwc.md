# 青岛大学 - 教务处通知

## Coverage
`index-only`

## Route
- Namespace: `qdu`
- Namespace Name: `青岛大学`
- Route Path: `/jwc`
- Route Name: `教务处通知`
- Example: `/qdu/jwc`
- URL: `jwc.qdu.edu.cn/jwtz.htm`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `abc1763613206`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/qdu/jwc.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `jwc.qdu.edu.cn/jwtz.htm`
  - `jwc.qdu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/qdu/jwc",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "abc1763613206"
  ],
  "module": "() => import('@/routes/qdu/jwc.ts')",
  "name": "教务处通知",
  "parameters": {},
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.qdu.edu.cn/jwtz.htm",
        "jwc.qdu.edu.cn/"
      ]
    }
  ],
  "url": "jwc.qdu.edu.cn/jwtz.htm"
}
```
