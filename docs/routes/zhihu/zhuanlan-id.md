# 知乎 - 专栏

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhuanlan/:id`
- Route Name: `专栏`
- Example: `/zhihu/zhuanlan/googledevelopers`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `zhuanlan.ts`
- Source Module: `() => import('@/routes/zhihu/zhuanlan.ts')`

## Description
_None_

## Parameters
- `id`: 专栏 id，可在专栏主页 URL 中找到


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
  - `zhuanlan.zhihu.com/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/zhuanlan/googledevelopers",
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
  "location": "zhuanlan.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/zhihu/zhuanlan.ts')",
  "name": "专栏",
  "parameters": {
    "id": "专栏 id，可在专栏主页 URL 中找到"
  },
  "path": "/zhuanlan/:id",
  "radar": [
    {
      "source": [
        "zhuanlan.zhihu.com/:id"
      ]
    }
  ]
}
```
