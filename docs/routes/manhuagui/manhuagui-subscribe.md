# 看漫画 - 漫画个人订阅

## Coverage
`index-only`

## Route
- Namespace: `manhuagui`
- Namespace Name: `看漫画`
- Route Path: `/manhuagui/subscribe`
- Route Name: `漫画个人订阅`
- Example: `/manhuagui/subscribe`
- URL: `www.mhgui.com/user/book/shelf`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `shininome`
- Source Location: `subscribe.tsx`
- Source Module: `_None_`

## Description
::: tip
个人订阅需要自建
环境变量需要添加 MHGUI\_COOKIE
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
  "description": "::: tip\n个人订阅需要自建\n环境变量需要添加 MHGUI\\_COOKIE\n:::",
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
  "heat": 0,
  "location": "subscribe.tsx",
  "maintainers": [
    "shininome"
  ],
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
  "topFeeds": [],
  "url": "www.mhgui.com/user/book/shelf"
}
```
