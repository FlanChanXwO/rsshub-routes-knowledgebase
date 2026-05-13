# Blizzard - 暴雪游戏国服新闻

## Coverage
`index-only`

## Route
- Namespace: `blizzard`
- Namespace Name: `Blizzard`
- Route Path: `/news-cn/:category?`
- Route Name: `暴雪游戏国服新闻`
- Example: `/blizzard/news-cn/ow`
- URL: `news.blizzard.com`
- Language: `en`
- Categories: `game`
- Maintainers: `zhangpeng2k`
- Source Location: `news-cn.ts`
- Source Module: `() => import('@/routes/blizzard/news-cn.ts')`

## Description
| 守望先锋 | 炉石传说 | 魔兽世界 |
|----------|----------|---------|
| ow       | hs       | wow     |

## Parameters
- `category`: 游戏类别, 默认为 ow


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
  - `ow.blizzard.cn`
- `target`: `/news-cn/`
### Rule 2
- `source`:
  - `wow.blizzard.cn`
- `target`: `/news-cn/`
### Rule 3
- `source`:
  - `hs.blizzard.cn`
- `target`: `/news-cn/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "\n| 守望先锋 | 炉石传说 | 魔兽世界 |\n|----------|----------|---------|\n| ow       | hs       | wow     |\n",
  "example": "/blizzard/news-cn/ow",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news-cn.ts",
  "maintainers": [
    "zhangpeng2k"
  ],
  "module": "() => import('@/routes/blizzard/news-cn.ts')",
  "name": "暴雪游戏国服新闻",
  "parameters": {
    "category": "游戏类别, 默认为 ow"
  },
  "path": "/news-cn/:category?",
  "radar": [
    {
      "source": [
        "ow.blizzard.cn"
      ],
      "target": "/news-cn/"
    },
    {
      "source": [
        "wow.blizzard.cn"
      ],
      "target": "/news-cn/"
    },
    {
      "source": [
        "hs.blizzard.cn"
      ],
      "target": "/news-cn/"
    }
  ]
}
```
