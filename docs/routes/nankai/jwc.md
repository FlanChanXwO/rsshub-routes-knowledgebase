# 南开大学 - 教务处通知公告

## Coverage
`index-only`

## Route
- Namespace: `nankai`
- Namespace Name: `南开大学`
- Route Path: `/jwc`
- Route Name: `教务处通知公告`
- Example: `/nankai/jwc`
- URL: `jwc.nankai.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `vicguo0724`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/nankai/jwc.ts')`

## Description
南开大学教务处通知公告

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
  - `jwc.nankai.edu.cn/tzgg/list.htm`
- `target`: `/jwc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "南开大学教务处通知公告",
  "example": "/nankai/jwc",
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
    "vicguo0724"
  ],
  "module": "() => import('@/routes/nankai/jwc.ts')",
  "name": "教务处通知公告",
  "parameters": {},
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.nankai.edu.cn/tzgg/list.htm"
      ],
      "target": "/jwc"
    }
  ],
  "url": "jwc.nankai.edu.cn"
}
```
