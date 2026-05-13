# 中国石油大学（华东） - 研究生院通知公告

## Coverage
`index-only`

## Route
- Namespace: `upc`
- Namespace Name: `中国石油大学（华东）`
- Route Path: `/yjs`
- Route Name: `研究生院通知公告`
- Example: `/upc/yjs`
- URL: `zs.gs.upc.edu.cn/sszs/list.htm`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `shengmaosu`
- Source Location: `yjs.ts`
- Source Module: `() => import('@/routes/upc/yjs.ts')`

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
  - `zs.gs.upc.edu.cn/sszs/list.htm`
  - `zs.gs.upc.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/upc/yjs",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yjs.ts",
  "maintainers": [
    "shengmaosu"
  ],
  "module": "() => import('@/routes/upc/yjs.ts')",
  "name": "研究生院通知公告",
  "parameters": {},
  "path": "/yjs",
  "radar": [
    {
      "source": [
        "zs.gs.upc.edu.cn/sszs/list.htm",
        "zs.gs.upc.edu.cn/"
      ]
    }
  ],
  "url": "zs.gs.upc.edu.cn/sszs/list.htm"
}
```
