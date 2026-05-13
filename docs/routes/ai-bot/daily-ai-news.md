# AI工具集 - 每日AI资讯

## Coverage
`index-only`

## Route
- Namespace: `ai-bot`
- Namespace Name: `AI工具集`
- Route Path: `/daily-ai-news`
- Route Name: `每日AI资讯`
- Example: `/ai-bot/daily-ai-news`
- URL: `ai-bot.cn/daily-ai-news`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `redwood9`
- Source Location: `daily-ai-news.ts`
- Source Module: `() => import('@/routes/ai-bot/daily-ai-news.ts')`

## Description
获取 AI 工具集网站的每日 AI 资讯汇总。

## Parameters
_None_


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
  - `ai-bot.cn/daily-ai-news`
  - `ai-bot.cn/daily-ai-news/`
- `target`: `/daily-ai-news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "获取 AI 工具集网站的每日 AI 资讯汇总。",
  "example": "/ai-bot/daily-ai-news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "daily-ai-news.ts",
  "maintainers": [
    "redwood9"
  ],
  "module": "() => import('@/routes/ai-bot/daily-ai-news.ts')",
  "name": "每日AI资讯",
  "parameters": {},
  "path": "/daily-ai-news",
  "radar": [
    {
      "source": [
        "ai-bot.cn/daily-ai-news",
        "ai-bot.cn/daily-ai-news/"
      ],
      "target": "/daily-ai-news"
    }
  ],
  "url": "ai-bot.cn/daily-ai-news"
}
```
