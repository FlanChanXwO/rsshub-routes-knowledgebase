# 华南师范大学 - 教务处通知

## Coverage
`index-only`

## Route
- Namespace: `scnu`
- Namespace Name: `华南师范大学`
- Route Path: `/jw`
- Route Name: `教务处通知`
- Example: `/scnu/jw`
- URL: `jw.scnu.edu.cn/ann/index.html`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `fengkx`
- Source Location: `jw.ts`
- Source Module: `() => import('@/routes/scnu/jw.ts')`

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
  - `jw.scnu.edu.cn/ann/index.html`
  - `jw.scnu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/scnu/jw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jw.ts",
  "maintainers": [
    "fengkx"
  ],
  "module": "() => import('@/routes/scnu/jw.ts')",
  "name": "教务处通知",
  "parameters": {},
  "path": "/jw",
  "radar": [
    {
      "source": [
        "jw.scnu.edu.cn/ann/index.html",
        "jw.scnu.edu.cn/"
      ]
    }
  ],
  "url": "jw.scnu.edu.cn/ann/index.html"
}
```
