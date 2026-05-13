# 金十数据 - 主题文章

## Coverage
`index-only`

## Route
- Namespace: `jin10`
- Namespace Name: `金十数据`
- Route Path: `/topic/:id`
- Route Name: `主题文章`
- Example: `/jin10/topic/396`
- URL: `jin10.com/`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `miles170`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/jin10/topic.ts')`

## Description
_None_

## Parameters
- `id`: N


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
  - `xnews.jin10.com/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/jin10/topic/396",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topic.ts",
  "maintainers": [
    "miles170"
  ],
  "module": "() => import('@/routes/jin10/topic.ts')",
  "name": "主题文章",
  "parameters": {
    "id": "N"
  },
  "path": "/topic/:id",
  "radar": [
    {
      "source": [
        "xnews.jin10.com/topic/:id"
      ]
    }
  ],
  "url": "jin10.com/",
  "view": 0
}
```
