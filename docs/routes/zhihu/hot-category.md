# 知乎 - 知乎热榜

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/hot/:category?`
- Route Name: `知乎热榜`
- Example: `/zhihu/hot`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `nczitzk, pseudoyu, DIYgod`
- Source Location: `hot.ts`
- Source Module: `() => import('@/routes/zhihu/hot.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/hot",
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
  "location": "hot.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu",
    "DIYgod"
  ],
  "module": "() => import('@/routes/zhihu/hot.ts')",
  "name": "知乎热榜",
  "path": "/hot/:category?",
  "view": 0
}
```
