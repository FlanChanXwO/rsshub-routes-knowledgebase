# DW Deutsche Welle - RSS

## Coverage
`index-only`

## Route
- Namespace: `dw`
- Namespace Name: `DW Deutsche Welle`
- Route Path: `/rss/:channel?`
- Route Name: `RSS`
- Example: `/dw/rss/rss-en-all`
- URL: `dw.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `rss.ts`
- Source Module: `() => import('@/routes/dw/rss.ts')`

## Description
For a full list of RSS Feed Channels in English, please refer to [DW RSS Feeds](https://corporate.dw.com/en/rss-feeds/a-68693346).
RSS Feed Channels in other languages are also available, for example: `rss-chi-all` renders the RSS feed in Chinese and `rss-de-all` for the RSS Feed in German

## Parameters
- `category`: RSS Feed Channel, see below, `rss-en-all` by default


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "\nFor a full list of RSS Feed Channels in English, please refer to [DW RSS Feeds](https://corporate.dw.com/en/rss-feeds/a-68693346).\nRSS Feed Channels in other languages are also available, for example: `rss-chi-all` renders the RSS feed in Chinese and `rss-de-all` for the RSS Feed in German\n",
  "example": "/dw/rss/rss-en-all",
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
    "quiniapiezoelectricity"
  ],
  "module": "() => import('@/routes/dw/rss.ts')",
  "name": "RSS",
  "parameters": {
    "category": "RSS Feed Channel, see below, `rss-en-all` by default"
  },
  "path": "/rss/:channel?"
}
```
