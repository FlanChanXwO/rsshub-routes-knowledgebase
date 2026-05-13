# 什么值得买 - 关键词

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/keyword/:keyword`
- Route Name: `关键词`
- Example: `/smzdm/keyword/女装`
- URL: `post.smzdm.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `DIYgod, MeanZhang`
- Source Location: `keyword.ts`
- Source Module: `() => import('@/routes/smzdm/keyword.ts')`

## Description
_None_

## Parameters
- `keyword`: 你想订阅的关键词


## Features
- `requireConfig`: [{"description": "什么值得买登录后的 Cookie 值", "name": "SMZDM_COOKIE"}]
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
    "shopping"
  ],
  "example": "/smzdm/keyword/女装",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "什么值得买登录后的 Cookie 值",
        "name": "SMZDM_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "keyword.ts",
  "maintainers": [
    "DIYgod",
    "MeanZhang"
  ],
  "module": "() => import('@/routes/smzdm/keyword.ts')",
  "name": "关键词",
  "parameters": {
    "keyword": "你想订阅的关键词"
  },
  "path": "/keyword/:keyword",
  "view": 5
}
```
