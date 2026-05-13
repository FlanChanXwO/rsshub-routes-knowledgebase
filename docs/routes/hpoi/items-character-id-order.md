# Hpoi 手办维基 - 角色周边

## Coverage
`index-only`

## Route
- Namespace: `hpoi`
- Namespace Name: `Hpoi 手办维基`
- Route Path: `/items/character/:id/:order?`
- Route Name: `角色周边`
- Example: `/hpoi/items/character/1035374`
- URL: `www.hpoi.net`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `DIYgod`
- Source Location: `character.ts`
- Source Module: `() => import('@/routes/hpoi/character.ts')`

## Description
_None_

## Parameters
- `id`: 角色 ID
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
  "example": "/hpoi/items/character/1035374",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "character.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/hpoi/character.ts')",
  "name": "角色周边",
  "parameters": {
    "id": "角色 ID",
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
  "path": "/items/character/:id/:order?",
  "view": 2
}
```
