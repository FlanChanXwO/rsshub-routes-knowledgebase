# 简书 - 专题

## Coverage
`index-only`

## Route
- Namespace: `jianshu`
- Namespace Name: `简书`
- Route Path: `/collection/:id`
- Route Name: `专题`
- Example: `/jianshu/collection/xYuZYD`
- URL: `www.jianshu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod, HenryQW, JimenezLi`
- Source Location: `collection.ts`
- Source Module: `() => import('@/routes/jianshu/collection.ts')`

## Description
_None_

## Parameters
- `id`: 专题 id, 可在专题页 URL 中找到


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
  - `www.jianshu.com/c/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/jianshu/collection/xYuZYD",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "collection.ts",
  "maintainers": [
    "DIYgod",
    "HenryQW",
    "JimenezLi"
  ],
  "module": "() => import('@/routes/jianshu/collection.ts')",
  "name": "专题",
  "parameters": {
    "id": "专题 id, 可在专题页 URL 中找到"
  },
  "path": "/collection/:id",
  "radar": [
    {
      "source": [
        "www.jianshu.com/c/:id"
      ]
    }
  ],
  "view": 0
}
```
