# 国家能源局 - 贵州省教育厅 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/guizhou/jyt/tzgg`
- Route Name: `贵州省教育厅 - 通知公告`
- Example: `/gov/guizhou/jyt/tzgg`
- URL: `jyt.guizhou.gov.cn/zwgk/tzgg/`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `sheetung`
- Source Location: `guizhou/jyt.ts`
- Source Module: `() => import('@/routes/gov/guizhou/jyt.ts')`

## Description
贵州省教育厅官方网站通知公告RSS源

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
  - `jyt.guizhou.gov.cn/zwgk/tzgg/`
  - `jyt.guizhou.gov.cn/zwgk/tzgg/index.html`
- `target`: `/guizhou/jyt/tzgg`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "贵州省教育厅官方网站通知公告RSS源",
  "example": "/gov/guizhou/jyt/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "guizhou/jyt.ts",
  "maintainers": [
    "sheetung"
  ],
  "module": "() => import('@/routes/gov/guizhou/jyt.ts')",
  "name": "贵州省教育厅 - 通知公告",
  "parameters": {},
  "path": "/guizhou/jyt/tzgg",
  "radar": [
    {
      "source": [
        "jyt.guizhou.gov.cn/zwgk/tzgg/",
        "jyt.guizhou.gov.cn/zwgk/tzgg/index.html"
      ],
      "target": "/guizhou/jyt/tzgg"
    }
  ],
  "url": "jyt.guizhou.gov.cn/zwgk/tzgg/"
}
```
