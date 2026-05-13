# 看漫画 - 漫画个人订阅

## Coverage
`index-only`

## Route
- Namespace: `manhuagui`
- Namespace Name: `看漫画`
- Route Path: `/subscribe`
- Route Name: `漫画个人订阅`
- Example: `/manhuagui/subscribe`
- URL: `www.mhgui.com/user/book/shelf`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `shininome`
- Source Location: `subscribe.tsx`
- Source Module: `() => import('@/routes/manhuagui/subscribe.tsx')`

## Description
::: tip
  个人订阅需要自建
  环境变量需要添加 MHGUI_COOKIE
:::

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "", "name": "MHGUI_COOKIE"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.mhgui.com/user/book/shelf`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: tip\n  个人订阅需要自建\n  环境变量需要添加 MHGUI_COOKIE\n:::",
  "example": "/manhuagui/subscribe",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "",
        "name": "MHGUI_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "subscribe.tsx",
  "maintainers": [
    "shininome"
  ],
  "module": "() => import('@/routes/manhuagui/subscribe.tsx')",
  "name": "漫画个人订阅",
  "parameters": {},
  "path": "/subscribe",
  "radar": [
    {
      "source": [
        "www.mhgui.com/user/book/shelf"
      ]
    }
  ],
  "url": "www.mhgui.com/user/book/shelf"
}
```
