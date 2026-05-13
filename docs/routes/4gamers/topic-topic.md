# 4Gamers - 主題

## Coverage
`index-only`

## Route
- Namespace: `4gamers`
- Namespace Name: `4Gamers`
- Route Path: `/topic/:topic`
- Route Name: `主題`
- Example: `/4gamers/topic/gentlemen-topic`
- URL: `www.4gamers.com.tw/news`
- Language: `zh-TW`
- Categories: `game`
- Maintainers: `bestpika`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/4gamers/topic.ts')`

## Description
_None_

## Parameters
- `topic`: 主题，可在首页上方页面内找到


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
  - `www.4gamers.com.tw/news/option-cfg/:topic`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/4gamers/topic/gentlemen-topic",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topic.ts",
  "maintainers": [
    "bestpika"
  ],
  "module": "() => import('@/routes/4gamers/topic.ts')",
  "name": "主題",
  "parameters": {
    "topic": "主题，可在首页上方页面内找到"
  },
  "path": "/topic/:topic",
  "radar": [
    {
      "source": [
        "www.4gamers.com.tw/news/option-cfg/:topic"
      ]
    }
  ],
  "url": "www.4gamers.com.tw/news"
}
```
