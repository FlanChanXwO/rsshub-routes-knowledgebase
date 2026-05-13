# Inoreader - RSS

## Coverage
`index-only`

## Route
- Namespace: `inoreader`
- Namespace Name: `Inoreader`
- Route Path: `/rss/:user/:tag`
- Route Name: `RSS`
- Example: `/inoreader/rss/1005137674/user-favorites`
- URL: `inoreader.com`
- Language: `en`
- Categories: `reading`
- Maintainers: `EthanWng97`
- Source Location: `rss.ts`
- Source Module: `() => import('@/routes/inoreader/rss.ts')`

## Description
_None_

## Parameters
- `user`: user id, the interger after user/ in the example URL
- `tag`: tag, the string after tag/ in the example URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/inoreader/rss/1005137674/user-favorites",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "rss.ts",
  "maintainers": [
    "EthanWng97"
  ],
  "module": "() => import('@/routes/inoreader/rss.ts')",
  "name": "RSS",
  "parameters": {
    "tag": "tag, the string after tag/ in the example URL",
    "user": "user id, the interger after user/ in the example URL"
  },
  "path": "/rss/:user/:tag",
  "view": 0
}
```
