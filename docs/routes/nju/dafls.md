# 南京大学 - 大学外语部

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/dafls`
- Route Name: `大学外语部`
- Example: `/nju/dafls`
- URL: `dafls.nju.edu.cn/13167/list.html`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `dafls.ts`
- Source Module: `() => import('@/routes/nju/dafls.ts')`

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
  - `dafls.nju.edu.cn/13167/list.html`
  - `dafls.nju.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/nju/dafls",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dafls.ts",
  "maintainers": [
    "ret-1"
  ],
  "module": "() => import('@/routes/nju/dafls.ts')",
  "name": "大学外语部",
  "parameters": {},
  "path": "/dafls",
  "radar": [
    {
      "source": [
        "dafls.nju.edu.cn/13167/list.html",
        "dafls.nju.edu.cn/"
      ]
    }
  ],
  "url": "dafls.nju.edu.cn/13167/list.html"
}
```
