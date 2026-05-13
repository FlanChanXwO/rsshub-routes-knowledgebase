# 知乎 - 用户全部收藏内容

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/people/allCollections/:id`
- Route Name: `用户全部收藏内容`
- Example: `/zhihu/people/allCollections/87-44-49-67`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `Healthyyue`
- Source Location: `all-collections.ts`
- Source Module: `() => import('@/routes/zhihu/all-collections.ts')`

## Description
_None_

## Parameters
- `id`: 作者 id，可在用户主页 URL 中找到


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
  - `www.zhihu.com/people/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/people/allCollections/87-44-49-67",
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
  "location": "all-collections.ts",
  "maintainers": [
    "Healthyyue"
  ],
  "module": "() => import('@/routes/zhihu/all-collections.ts')",
  "name": "用户全部收藏内容",
  "parameters": {
    "id": "作者 id，可在用户主页 URL 中找到"
  },
  "path": "/people/allCollections/:id",
  "radar": [
    {
      "source": [
        "www.zhihu.com/people/:id"
      ]
    }
  ],
  "view": 0
}
```
