# 东南大学 - 研究生院全部公告

## Coverage
`index-only`

## Route
- Namespace: `seu`
- Namespace Name: `东南大学`
- Route Path: `/yjs`
- Route Name: `研究生院全部公告`
- Example: `/seu/yjs`
- URL: `seugs.seu.edu.cn/26671/list.htm`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Denkiyohou`
- Source Location: `yjs.ts`
- Source Module: `() => import('@/routes/seu/yjs.ts')`

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
  - `seugs.seu.edu.cn/26671/list.htm`
  - `seugs.seu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/seu/yjs",
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
    "Denkiyohou"
  ],
  "module": "() => import('@/routes/seu/yjs.ts')",
  "name": "研究生院全部公告",
  "parameters": {},
  "path": "/yjs",
  "radar": [
    {
      "source": [
        "seugs.seu.edu.cn/26671/list.htm",
        "seugs.seu.edu.cn/"
      ]
    }
  ],
  "url": "seugs.seu.edu.cn/26671/list.htm"
}
```
