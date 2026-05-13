# 南京大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/gra`
- Route Name: `研究生院`
- Example: `/nju/gra`
- URL: `grawww.nju.edu.cn/main.htm`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `gra.ts`
- Source Module: `() => import('@/routes/nju/gra.ts')`

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
  - `grawww.nju.edu.cn/main.htm`
  - `grawww.nju.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/nju/gra",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gra.ts",
  "maintainers": [
    "ret-1"
  ],
  "module": "() => import('@/routes/nju/gra.ts')",
  "name": "研究生院",
  "parameters": {},
  "path": "/gra",
  "radar": [
    {
      "source": [
        "grawww.nju.edu.cn/main.htm",
        "grawww.nju.edu.cn/"
      ]
    }
  ],
  "url": "grawww.nju.edu.cn/main.htm"
}
```
