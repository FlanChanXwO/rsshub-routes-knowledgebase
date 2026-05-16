# 4Gamers - 主題

## Coverage
`index-only`

## Route
- Namespace: `4gamers`
- Namespace Name: `4Gamers`
- Route Path: `/4gamers/topic/:topic`
- Route Name: `主題`
- Example: `/4gamers/topic/gentlemen-topic`
- URL: `www.4gamers.com.tw/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `bestpika`
- Source Location: `topic.ts`
- Source Module: `_None_`

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
  "heat": 4,
  "location": "topic.ts",
  "maintainers": [
    "bestpika"
  ],
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
  "topFeeds": [
    {
      "description": "4Gamers - gentlemen-topic - Powered by RSSHub",
      "errorAt": "2026-02-23T07:49:01.760Z",
      "errorMessage": "Unhandled section type: InsertOneAdsSection on https://www.4gamers.com.tw/news/detail/78987/black-gold-shining-town-steam-page-released\n",
      "id": "83442528914522112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.4gamers.com.tw/news/option-cfg/gentlemen-topic",
      "title": "4Gamers - gentlemen-topic",
      "type": "feed",
      "url": "rsshub://4gamers/topic/gentlemen-topic"
    }
  ],
  "url": "www.4gamers.com.tw/news"
}
```
