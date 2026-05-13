# 微博 - 关键词

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/keyword/:keyword/:routeParams?`
- Route Name: `关键词`
- Example: `/weibo/keyword/RSSHub`
- URL: `weibo.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod, Rongronggg9`
- Source Location: `keyword.ts`
- Source Module: `() => import('@/routes/weibo/keyword.ts')`

## Description
_None_

## Parameters
- `keyword`: 你想订阅的微博关键词
- `routeParams`: 额外参数；请参阅上面的说明和表格


## Features
- `requireConfig`: [{"description": "", "name": "WEIBO_COOKIES", "optional": true}]
- `requirePuppeteer`: true
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
    "social-media"
  ],
  "example": "/weibo/keyword/RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "WEIBO_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "keyword.ts",
  "maintainers": [
    "DIYgod",
    "Rongronggg9"
  ],
  "module": "() => import('@/routes/weibo/keyword.ts')",
  "name": "关键词",
  "parameters": {
    "keyword": "你想订阅的微博关键词",
    "routeParams": "额外参数；请参阅上面的说明和表格"
  },
  "path": "/keyword/:keyword/:routeParams?",
  "view": 1
}
```
