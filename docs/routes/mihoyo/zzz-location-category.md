# 米哈游 - 绝区零

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/zzz/:location?/:category?`
- Route Name: `绝区零`
- Example: `/mihoyo/zzz`
- URL: `zzz.mihoyo.com/news`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `Yeye-0426`
- Source Location: `zzz/news.ts`
- Source Module: `() => import('@/routes/mihoyo/zzz/news.ts')`

## Description
#### 新闻 {#mi-ha-you-jue-qu-ling-xin-wen}

| 最新     | 新闻 | 公告   | 活动     |
| -------- | ---- | ------ | -------- |
| news-all | news | notice | activity |

## Parameters
- `location`: 区域，可选 `zh-cn`（国服，简中）或 `zh-tw`（国际服，繁中）
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
  - `zzz.mihoyo.com/news`
- `target`: `/zzz`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "#### 新闻 {#mi-ha-you-jue-qu-ling-xin-wen}\n\n| 最新     | 新闻 | 公告   | 活动     |\n| -------- | ---- | ------ | -------- |\n| news-all | news | notice | activity |",
  "example": "/mihoyo/zzz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "zzz/news.ts",
  "maintainers": [
    "Yeye-0426"
  ],
  "module": "() => import('@/routes/mihoyo/zzz/news.ts')",
  "name": "绝区零",
  "parameters": {
    "category": "分类，见下表，默认为最新",
    "location": "区域，可选 `zh-cn`（国服，简中）或 `zh-tw`（国际服，繁中）"
  },
  "path": "/zzz/:location?/:category?",
  "radar": [
    {
      "source": [
        "zzz.mihoyo.com/news"
      ],
      "target": "/zzz"
    }
  ],
  "url": "zzz.mihoyo.com/news"
}
```
