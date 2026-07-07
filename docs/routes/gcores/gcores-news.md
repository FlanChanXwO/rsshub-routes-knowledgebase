# 机核网 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/gcores/news`
- Route Name: `资讯`
- Example: `/gcores/news`
- URL: `www.gcores.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.gcores.com/news`
- `target`: `/gcores/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/gcores/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 320,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "资讯",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.gcores.com/news"
      ],
      "target": "/gcores/news"
    }
  ],
  "topFeeds": [
    {
      "description": "阅读机核关于游戏、影视、科技与流行文化的最新资讯。 - Powered by RSSHub",
      "errorAt": "2026-07-06T03:01:17.338Z",
      "errorMessage": "Failed query: select \"id\", \"guid\", \"media\" from \"entries\" \"entries\" where \"entries\".\"feed_id\" = $1\nparams: 106670430920170496",
      "id": "106670430920170496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gcores.com/news",
      "title": "资讯 | 机核 GCORES",
      "type": "feed",
      "url": "rsshub://gcores/news"
    }
  ],
  "url": "www.gcores.com",
  "view": 0
}
```
