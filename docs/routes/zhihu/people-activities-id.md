# 知乎 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/people/activities/:id`
- Route Name: `用户动态`
- Example: `/zhihu/people/activities/diygod`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `activities.ts`
- Source Module: `() => import('@/routes/zhihu/activities.ts')`

## Description
_None_

## Parameters
- `id`: 作者 id，可在用户主页 URL 中找到


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES", "optional": true}]
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
  "example": "/zhihu/people/activities/diygod",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "activities.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/zhihu/activities.ts')",
  "name": "用户动态",
  "parameters": {
    "id": "作者 id，可在用户主页 URL 中找到"
  },
  "path": "/people/activities/:id",
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
