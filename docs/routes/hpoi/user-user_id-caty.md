# Hpoi 手办维基 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `hpoi`
- Namespace Name: `Hpoi 手办维基`
- Route Path: `/user/:user_id/:caty`
- Route Name: `用户动态`
- Example: `/hpoi/user/116297/buy`
- URL: `www.hpoi.net`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `DIYgod, luyuhuang`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/hpoi/user.ts')`

## Description
_None_

## Parameters
- `user_id`: {"description": "用户ID"}
- `caty`: {"default": "buy", "description": "类别", "options": [{"label": "想买", "value": "want"}, {"label": "预定", "value": "preorder"}, {"label": "已入", "value": "buy"}, {"label": "关注", "value": "care"}, {"label": "有过", "value": "resell"}]}


## Features
- `requireConfig`: false
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
    "anime"
  ],
  "example": "/hpoi/user/116297/buy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "DIYgod",
    "luyuhuang"
  ],
  "module": "() => import('@/routes/hpoi/user.ts')",
  "name": "用户动态",
  "parameters": {
    "caty": {
      "default": "buy",
      "description": "类别",
      "options": [
        {
          "label": "想买",
          "value": "want"
        },
        {
          "label": "预定",
          "value": "preorder"
        },
        {
          "label": "已入",
          "value": "buy"
        },
        {
          "label": "关注",
          "value": "care"
        },
        {
          "label": "有过",
          "value": "resell"
        }
      ]
    },
    "user_id": {
      "description": "用户ID"
    }
  },
  "path": "/user/:user_id/:caty"
}
```
