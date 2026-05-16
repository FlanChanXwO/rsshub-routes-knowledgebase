# 搜狐号 - 首页新闻

## Coverage
`index-only`

## Route
- Namespace: `sohu`
- Namespace Name: `搜狐号`
- Route Path: `/sohu/mobile`
- Route Name: `首页新闻`
- Example: `/sohu/mobile`
- URL: `sohu.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `asqwe1`
- Source Location: `mobile.ts`
- Source Module: `_None_`

## Description
订阅手机搜狐网的首页新闻

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
  - `m.sohu.com/limit`
- `target`: `/mobile`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "订阅手机搜狐网的首页新闻",
  "example": "/sohu/mobile",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 17,
  "location": "mobile.ts",
  "maintainers": [
    "asqwe1"
  ],
  "name": "首页新闻",
  "parameters": {},
  "path": "/mobile",
  "radar": [
    {
      "source": [
        "m.sohu.com/limit"
      ],
      "target": "/mobile"
    }
  ],
  "topFeeds": [
    {
      "description": "手机搜狐新闻 - Powered by RSSHub",
      "errorAt": "2026-05-14T23:47:17.741Z",
      "errorMessage": "Failed to fetch\n",
      "id": "141055454808791040",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.sohu.com/limit",
      "title": "手机搜狐新闻",
      "type": "feed",
      "url": "rsshub://sohu/mobile"
    }
  ]
}
```
