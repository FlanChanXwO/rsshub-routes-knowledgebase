# 中指研究院 - 报告

## Coverage
`index-only`

## Route
- Namespace: `cih-index`
- Namespace Name: `中指研究院`
- Route Path: `/report/list/:report?`
- Route Name: `报告`
- Example: `/cih-index/report/list/p1-oaddtime-ddesc`
- URL: `www.cih-index.com/report/list/p1-oaddtime-ddesc`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `report.ts`
- Source Module: `() => import('@/routes/cih-index/report.ts')`

## Description
_None_

## Parameters
- `report`: 报告 id，可在 URL 中找到，留空为 `p1-oaddtime-ddesc`


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
  - `www.cih-index.com/report/list/:report`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/cih-index/report/list/p1-oaddtime-ddesc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "report.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/cih-index/report.ts')",
  "name": "报告",
  "parameters": {
    "report": "报告 id，可在 URL 中找到，留空为 `p1-oaddtime-ddesc`"
  },
  "path": "/report/list/:report?",
  "radar": [
    {
      "source": [
        "www.cih-index.com/report/list/:report"
      ]
    }
  ],
  "url": "www.cih-index.com/report/list/p1-oaddtime-ddesc"
}
```
