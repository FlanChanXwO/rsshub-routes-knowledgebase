# 直播吧 - 滚动新闻

## Coverage
`index-only`

## Route
- Namespace: `zhibo8`
- Namespace Name: `直播吧`
- Route Path: `/more/:category?`
- Route Name: `滚动新闻`
- Example: `/zhibo8/more/nba`
- URL: `zhibo8.cc`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `more.ts`
- Source Module: `() => import('@/routes/zhibo8/more.ts')`

## Description
| NBA | 足球  | 电竞     | 综合   |
| --- | ----- | -------- | ------ |
| nba | zuqiu | dianjing | zonghe |

## Parameters
- `category`: 分类，见下表，默认为 NBA


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
  - `news.zhibo8.cc/:category`
- `target`: `/more/:category`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "\n| NBA | 足球  | 电竞     | 综合   |\n| --- | ----- | -------- | ------ |\n| nba | zuqiu | dianjing | zonghe |",
  "example": "/zhibo8/more/nba",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "more.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/zhibo8/more.ts')",
  "name": "滚动新闻",
  "parameters": {
    "category": "分类，见下表，默认为 NBA"
  },
  "path": "/more/:category?",
  "radar": [
    {
      "source": [
        "news.zhibo8.cc/:category"
      ],
      "target": "/more/:category"
    }
  ]
}
```
