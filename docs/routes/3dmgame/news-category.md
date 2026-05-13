# 3DMGame - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `3dmgame`
- Namespace Name: `3DMGame`
- Route Path: `/news/:category?`
- Route Name: `新闻中心`
- Example: `/3dmgame/news`
- URL: `3dmgame.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `zhboner, lyqluis`
- Source Location: `news-center.ts`
- Source Module: `() => import('@/routes/3dmgame/news-center.ts')`

## Description
| 新闻推荐 | 游戏新闻 | 动漫影视 | 智能数码 | 时事焦点    |
| -------- | -------- | -------- | -------- | ----------- |
|          | game     | acg      | next     | news_36_1 |

## Parameters
- `category`: 分类名或 ID，见下表，默认为新闻推荐，ID 可从分类 URL 中找到，如 Steam 为 `22221`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `3dmgame.com/news/:category?`
  - `3dmgame.com/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 新闻推荐 | 游戏新闻 | 动漫影视 | 智能数码 | 时事焦点    |\n| -------- | -------- | -------- | -------- | ----------- |\n|          | game     | acg      | next     | news_36_1 |",
  "example": "/3dmgame/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news-center.ts",
  "maintainers": [
    "zhboner",
    "lyqluis"
  ],
  "module": "() => import('@/routes/3dmgame/news-center.ts')",
  "name": "新闻中心",
  "parameters": {
    "category": "分类名或 ID，见下表，默认为新闻推荐，ID 可从分类 URL 中找到，如 Steam 为 `22221`"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "3dmgame.com/news/:category?",
        "3dmgame.com/news"
      ]
    }
  ]
}
```
