# 知乎 - xhu - 收藏夹

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/xhu/collection/:id`
- Route Name: `xhu - 收藏夹`
- Example: `/zhihu/xhu/collection/26444956`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/collection.ts`
- Source Module: `() => import('@/routes/zhihu/xhu/collection.ts')`

## Description
_None_

## Parameters
- `id`: 收藏夹 id, 可在收藏夹页面 URL 中找到


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
  - `www.zhihu.com/collection/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/xhu/collection/26444956",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "xhu/collection.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "module": "() => import('@/routes/zhihu/xhu/collection.ts')",
  "name": "xhu - 收藏夹",
  "parameters": {
    "id": "收藏夹 id, 可在收藏夹页面 URL 中找到"
  },
  "path": "/xhu/collection/:id",
  "radar": [
    {
      "source": [
        "www.zhihu.com/collection/:id"
      ]
    }
  ]
}
```
