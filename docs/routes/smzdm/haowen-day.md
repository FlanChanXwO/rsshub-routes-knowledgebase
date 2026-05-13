# 什么值得买 - 好文

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/haowen/:day?`
- Route Name: `好文`
- Example: `/smzdm/haowen/1`
- URL: `post.smzdm.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `LogicJake, pseudoyu`
- Source Location: `haowen.ts`
- Source Module: `() => import('@/routes/smzdm/haowen.ts')`

## Description
_None_

## Parameters
- `day`: {"default": "1", "description": "以天为时间跨度，默认为 `1`", "options": [{"label": "今日热门", "value": "1"}, {"label": "周热门", "value": "7"}, {"label": "月热门", "value": "30"}]}


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
  "example": "/smzdm/haowen/1",
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
  "location": "haowen.ts",
  "maintainers": [
    "LogicJake",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/smzdm/haowen.ts')",
  "name": "好文",
  "parameters": {
    "day": {
      "default": "1",
      "description": "以天为时间跨度，默认为 `1`",
      "options": [
        {
          "label": "今日热门",
          "value": "1"
        },
        {
          "label": "周热门",
          "value": "7"
        },
        {
          "label": "月热门",
          "value": "30"
        }
      ]
    }
  },
  "path": "/haowen/:day?"
}
```
