# EA Games - APEX Legends 官网资讯

## Coverage
`index-only`

## Route
- Namespace: `ea`
- Namespace Name: `EA Games`
- Route Path: `/apex-news/:lang?/:type?`
- Route Name: `APEX Legends 官网资讯`
- Example: `/ea/apex-news/zh-hant/game-updates`
- URL: `www.ea.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `IceChestnut`
- Source Location: `apex-news.ts`
- Source Module: `() => import('@/routes/ea/apex-news.ts')`

## Description
_None_

## Parameters
- `lang`: {"default": "en", "description": "语言", "options": [{"label": "中文(繁体)", "value": "zh-hant"}, {"label": "English", "value": "en"}]}
- `type`: {"default": "latest", "description": "资讯类型（可选）", "options": [{"label": "最新消息", "value": "news-article"}, {"label": "游戏更新", "value": "game-updates"}, {"label": "全部", "value": "latest"}]}


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
  "example": "/ea/apex-news/zh-hant/game-updates",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "apex-news.ts",
  "maintainers": [
    "IceChestnut"
  ],
  "module": "() => import('@/routes/ea/apex-news.ts')",
  "name": "APEX Legends 官网资讯",
  "parameters": {
    "lang": {
      "default": "en",
      "description": "语言",
      "options": [
        {
          "label": "中文(繁体)",
          "value": "zh-hant"
        },
        {
          "label": "English",
          "value": "en"
        }
      ]
    },
    "type": {
      "default": "latest",
      "description": "资讯类型（可选）",
      "options": [
        {
          "label": "最新消息",
          "value": "news-article"
        },
        {
          "label": "游戏更新",
          "value": "game-updates"
        },
        {
          "label": "全部",
          "value": "latest"
        }
      ]
    }
  },
  "path": "/apex-news/:lang?/:type?",
  "view": 0
}
```
