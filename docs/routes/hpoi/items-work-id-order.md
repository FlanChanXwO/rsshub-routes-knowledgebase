# Hpoi 手办维基 - 作品周边

## Coverage
`index-only`

## Route
- Namespace: `hpoi`
- Namespace Name: `Hpoi 手办维基`
- Route Path: `/items/work/:id/:order?`
- Route Name: `作品周边`
- Example: `/hpoi/items/work/4117491`
- URL: `www.hpoi.net`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `DIYgod`
- Source Location: `work.ts`
- Source Module: `() => import('@/routes/hpoi/work.ts')`

## Description
_None_

## Parameters
- `id`: 作品 ID
- `order`: {"default": "add", "description": "排序", "options": [{"label": "发售", "value": "release"}, {"label": "入库", "value": "add"}, {"label": "总热度", "value": "hits"}, {"label": "一周热度", "value": "hits7Day"}, {"label": "一天热度", "value": "hitsDay"}, {"label": "评价", "value": "rating"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/hpoi/items/work/4117491",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "work.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/hpoi/work.ts')",
  "name": "作品周边",
  "parameters": {
    "id": "作品 ID",
    "order": {
      "default": "add",
      "description": "排序",
      "options": [
        {
          "label": "发售",
          "value": "release"
        },
        {
          "label": "入库",
          "value": "add"
        },
        {
          "label": "总热度",
          "value": "hits"
        },
        {
          "label": "一周热度",
          "value": "hits7Day"
        },
        {
          "label": "一天热度",
          "value": "hitsDay"
        },
        {
          "label": "评价",
          "value": "rating"
        }
      ]
    }
  },
  "path": "/items/work/:id/:order?",
  "view": 2
}
```
