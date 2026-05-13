# 英雄联盟 - 台服新闻

## Coverage
`index-only`

## Route
- Namespace: `loltw`
- Namespace Name: `英雄联盟`
- Route Path: `/news/:category?`
- Route Name: `台服新闻`
- Example: `/loltw/news`
- URL: `lol.garena.tw`
- Language: `zh-TW`
- Categories: `game`
- Maintainers: `hoilc`
- Source Location: `news.tsx`
- Source Module: `() => import('@/routes/loltw/news.tsx')`

## Description
| 活动  | 资讯 | 系统   | 电竞   | 版本资讯 | 战棋资讯 |
| ----- | ---- | ------ | ------ | -------- | -------- |
| event | info | system | esport | patch    | TFTpatch |

## Parameters
- `category`: 新闻分类，置空为全部新闻


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
    "game"
  ],
  "description": "| 活动  | 资讯 | 系统   | 电竞   | 版本资讯 | 战棋资讯 |\n| ----- | ---- | ------ | ------ | -------- | -------- |\n| event | info | system | esport | patch    | TFTpatch |",
  "example": "/loltw/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.tsx",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/loltw/news.tsx')",
  "name": "台服新闻",
  "parameters": {
    "category": "新闻分类，置空为全部新闻"
  },
  "path": "/news/:category?"
}
```
