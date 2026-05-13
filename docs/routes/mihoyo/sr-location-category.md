# 米哈游 - 崩坏：星穹铁道

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/sr/:location?/:category?`
- Route Name: `崩坏：星穹铁道`
- Example: `/mihoyo/sr`
- URL: `sr.mihoyo.com/news`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `shinanory`
- Source Location: `sr/news.ts`
- Source Module: `() => import('@/routes/mihoyo/sr/news.ts')`

## Description
#### 新闻 {#mi-ha-you-beng-huai-xing-qiong-tie-dao-xin-wen}

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
  - `sr.mihoyo.com/news`
- `target`: `/sr`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "#### 新闻 {#mi-ha-you-beng-huai-xing-qiong-tie-dao-xin-wen}\n\n| 最新     | 新闻 | 公告   | 活动     |\n| -------- | ---- | ------ | -------- |\n| news-all | news | notice | activity |",
  "example": "/mihoyo/sr",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "sr/news.ts",
  "maintainers": [
    "shinanory"
  ],
  "module": "() => import('@/routes/mihoyo/sr/news.ts')",
  "name": "崩坏：星穹铁道",
  "parameters": {
    "category": "分类，见下表，默认为最新",
    "location": "区域，可选 `zh-cn`（国服，简中）或 `zh-tw`（国际服，繁中）"
  },
  "path": "/sr/:location?/:category?",
  "radar": [
    {
      "source": [
        "sr.mihoyo.com/news"
      ],
      "target": "/sr"
    }
  ],
  "url": "sr.mihoyo.com/news"
}
```
