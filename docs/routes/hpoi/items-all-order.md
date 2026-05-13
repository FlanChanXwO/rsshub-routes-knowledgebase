# Hpoi 手办维基 - 所有周边

## Coverage
`index-only`

## Route
- Namespace: `hpoi`
- Namespace Name: `Hpoi 手办维基`
- Route Path: `/items/all/:order?`
- Route Name: `所有周边`
- Example: `/hpoi/items/all`
- URL: `www.hpoi.net/hobby/all`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `DIYgod`
- Source Location: `all.ts`
- Source Module: `() => import('@/routes/hpoi/all.ts')`

## Description
_None_

## Parameters
- `order`: {"default": "add", "description": "排序", "options": [{"label": "发售", "value": "release"}, {"label": "入库", "value": "add"}, {"label": "总热度", "value": "hits"}, {"label": "一周热度", "value": "hits7Day"}, {"label": "一天热度", "value": "hitsDay"}, {"label": "评价", "value": "rating"}]}


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
  - `www.hpoi.net/hobby/all`
- `target`: `/items/all`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/hpoi/items/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "all.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/hpoi/all.ts')",
  "name": "所有周边",
  "parameters": {
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
  "path": "/items/all/:order?",
  "radar": [
    {
      "source": [
        "www.hpoi.net/hobby/all"
      ],
      "target": "/items/all"
    }
  ],
  "url": "www.hpoi.net/hobby/all",
  "view": 2
}
```
