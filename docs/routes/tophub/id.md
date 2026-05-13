# 今日热榜 - 榜单

## Coverage
`index-only`

## Route
- Namespace: `tophub`
- Namespace Name: `今日热榜`
- Route Path: `/:id`
- Route Name: `榜单`
- Example: `/tophub/Om4ejxvxEN`
- URL: `tophub.today`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `LogicJake`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/tophub/index.ts')`

## Description
_None_

## Parameters
- `id`: 榜单id，可在 URL 中找到


## Features
- `requireConfig`: [{"description": "", "name": "TOPHUB_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `tophub.today/n/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/tophub/Om4ejxvxEN",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "TOPHUB_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/tophub/index.ts')",
  "name": "榜单",
  "parameters": {
    "id": "榜单id，可在 URL 中找到"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "tophub.today/n/:id"
      ]
    }
  ]
}
```
