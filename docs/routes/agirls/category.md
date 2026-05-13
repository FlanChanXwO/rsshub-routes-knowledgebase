# 电獭少女 - 分类

## Coverage
`index-only`

## Route
- Namespace: `agirls`
- Namespace Name: `电獭少女`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/agirls/app`
- URL: `agirls.aotter.net`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `z-index.ts`
- Source Module: `() => import('@/routes/agirls/z-index.ts')`

## Description
| App 评测 | 手机开箱 | 笔电开箱 | 3C 周边     | 教学小技巧 | 科技情报 |
| -------- | -------- | -------- | ----------- | ---------- | -------- |
| app      | phone    | computer | accessories | tutorial   | techlife |

## Parameters
- `category`: 分类，默认为最新文章，可在对应主题页的 URL 中找到，下表仅列出部分


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
  - `agirls.aotter.net/posts/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| App 评测 | 手机开箱 | 笔电开箱 | 3C 周边     | 教学小技巧 | 科技情报 |\n| -------- | -------- | -------- | ----------- | ---------- | -------- |\n| app      | phone    | computer | accessories | tutorial   | techlife |",
  "example": "/agirls/app",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "z-index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/agirls/z-index.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类，默认为最新文章，可在对应主题页的 URL 中找到，下表仅列出部分"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "agirls.aotter.net/posts/:category"
      ],
      "target": "/:category"
    }
  ]
}
```
