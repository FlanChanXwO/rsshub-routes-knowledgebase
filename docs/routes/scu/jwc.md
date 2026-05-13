# 四川大学 - 教务处通知公告

## Coverage
`index-only`

## Route
- Namespace: `scu`
- Namespace Name: `四川大学`
- Route Path: `/jwc`
- Route Name: `教务处通知公告`
- Example: `/scu/jwc`
- URL: `www.scu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Kyle-You`
- Source Location: `jwc/tzgg.ts`
- Source Module: `() => import('@/routes/scu/jwc/tzgg.ts')`

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
  - `jwc.scu.edu.cn`
- `target`: `/jwc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/scu/jwc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc/tzgg.ts",
  "maintainers": [
    "Kyle-You"
  ],
  "module": "() => import('@/routes/scu/jwc/tzgg.ts')",
  "name": "教务处通知公告",
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.scu.edu.cn"
      ],
      "target": "/jwc"
    }
  ]
}
```
