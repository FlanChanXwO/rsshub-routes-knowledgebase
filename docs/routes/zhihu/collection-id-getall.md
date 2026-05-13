# 知乎 - 收藏夹

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/collection/:id/:getAll?`
- Route Name: `收藏夹`
- Example: `/zhihu/collection/26444956`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `huruji, Colin-XKL, Fatpandac`
- Source Location: `collection.ts`
- Source Module: `() => import('@/routes/zhihu/collection.ts')`

## Description
_None_

## Parameters
- `id`: 收藏夹 id，可在收藏夹页面 URL 中找到
- `getAll`: 获取全部收藏内容，任意值为打开


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES"}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.zhihu.com/collection/:id`
- `target`: `/collection/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/collection/26444956",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "collection.ts",
  "maintainers": [
    "huruji",
    "Colin-XKL",
    "Fatpandac"
  ],
  "module": "() => import('@/routes/zhihu/collection.ts')",
  "name": "收藏夹",
  "parameters": {
    "getAll": "获取全部收藏内容，任意值为打开",
    "id": "收藏夹 id，可在收藏夹页面 URL 中找到"
  },
  "path": "/collection/:id/:getAll?",
  "radar": [
    {
      "source": [
        "www.zhihu.com/collection/:id"
      ],
      "target": "/collection/:id"
    }
  ]
}
```
