# FastBull - News

## Coverage
`index-only`

## Route
- Namespace: `fastbull`
- Namespace Name: `FastBull`
- Route Path: `/fastbull/news`
- Route Name: `News`
- Example: `/fastbull/news`
- URL: `fastbull.com/news`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
_None_

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
  - `fastbull.com/cn/news`
  - `fastbull.com/cn`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/fastbull/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 184,
  "location": "news.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "fastbull.com/cn/news",
        "fastbull.com/cn"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "财经头条、财经新闻、最新资讯 - FastBull - Powered by RSSHub",
      "errorAt": "2026-05-15T00:42:38.068Z",
      "errorMessage": "Failed query: select \"id\", \"guid\", \"media\" from \"entries\" \"entries\" where \"entries\".\"feed_id\" = $1\nparams: 59799220289372189",
      "id": "59799220289372189",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.fastbull.com/cn/news",
      "title": "财经头条、财经新闻、最新资讯 - FastBull",
      "type": "feed",
      "url": "rsshub://fastbull/news"
    }
  ],
  "url": "fastbull.com/news",
  "view": 0
}
```
