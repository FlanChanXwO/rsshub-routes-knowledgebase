# 米哈游 - 原神

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/ys/:location?/:category?`
- Route Name: `原神`
- Example: `/mihoyo/ys`
- URL: `genshin.hoyoverse.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `ys/news.ts`
- Source Module: `() => import('@/routes/mihoyo/ys/news.ts')`

## Description
#### 新闻 {#mi-ha-you-yuan-shen-xin-wen}

| 最新   | 新闻 | 公告   | 活动     |
| ------ | ---- | ------ | -------- |
| latest | news | notice | activity |

## Parameters
- `location`: 区域，可选 `main`（简中）或 `zh-tw`（繁中）
- `category`: 分类，见下表，默认为最新


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
  - `genshin.hoyoverse.com/:location/news`
- `target`: `/ys/:location`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "#### 新闻 {#mi-ha-you-yuan-shen-xin-wen}\n\n| 最新   | 新闻 | 公告   | 活动     |\n| ------ | ---- | ------ | -------- |\n| latest | news | notice | activity |",
  "example": "/mihoyo/ys",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ys/news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/mihoyo/ys/news.ts')",
  "name": "原神",
  "parameters": {
    "category": "分类，见下表，默认为最新",
    "location": "区域，可选 `main`（简中）或 `zh-tw`（繁中）"
  },
  "path": "/ys/:location?/:category?",
  "radar": [
    {
      "source": [
        "genshin.hoyoverse.com/:location/news"
      ],
      "target": "/ys/:location"
    }
  ]
}
```
