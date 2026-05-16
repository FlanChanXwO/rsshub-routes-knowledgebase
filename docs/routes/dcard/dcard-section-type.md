# Dcard - 板塊帖子

## Coverage
`index-only`

## Route
- Namespace: `dcard`
- Namespace Name: `Dcard`
- Route Path: `/dcard/:section/:type?`
- Route Name: `板塊帖子`
- Example: `/dcard/funny/popular`
- URL: `www.dcard.tw`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `HenryQW`
- Source Location: `section.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `section`: 板塊名稱，URL 中獲得
- `type`: 排序，popular 熱門；latest 最新，默認為 latest


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/dcard/funny/popular",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "section.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "板塊帖子",
  "parameters": {
    "section": "板塊名稱，URL 中獲得",
    "type": "排序，popular 熱門；latest 最新，默認為 latest"
  },
  "path": "/:section/:type?",
  "topFeeds": []
}
```
