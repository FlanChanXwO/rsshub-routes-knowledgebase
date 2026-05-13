# CUPL - 教务处通知公告

## Coverage
`index-only`

## Route
- Namespace: `cupl`
- Namespace Name: `CUPL`
- Route Path: `/jwc`
- Route Name: `教务处通知公告`
- Example: `/cupl/jwc`
- URL: `jwc.cupl.edu.cn/index/tzgg.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Fgju`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/cupl/jwc.ts')`

## Description
中国政法大学教务处通知公告

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
  - `jwc.cupl.edu.cn/index/tzgg.htm`
  - `jwc.cupl.edu.cn/`
- `target`: `/jwc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "中国政法大学教务处通知公告",
  "example": "/cupl/jwc",
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
    "Fgju"
  ],
  "module": "() => import('@/routes/cupl/jwc.ts')",
  "name": "教务处通知公告",
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.cupl.edu.cn/index/tzgg.htm",
        "jwc.cupl.edu.cn/"
      ],
      "target": "/jwc"
    }
  ],
  "url": "jwc.cupl.edu.cn/index/tzgg.htm"
}
```
