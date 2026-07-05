# Radio Free Asia (RFA) 自由亚洲电台 - News

## Coverage
`index-only`

## Route
- Namespace: `rfa`
- Namespace Name: `Radio Free Asia (RFA) 自由亚洲电台`
- Route Path: `/rfa/:language?/:channel?/:subChannel?`
- Route Name: `News`
- Example: `/rfa/english`
- URL: `rfa.org`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `zphw`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Delivers a better experience by supporting parameter specification.

Parameters can be obtained from the official website, for instance:

`https://www.rfa.org/cantonese/news` corresponds to `/rfa/cantonese/news`

`https://www.rfa.org/cantonese/news/htm` corresponds to `/rfa/cantonese/news/htm`

## Parameters
- `language`: language, English by default
- `channel`: channel
- `subChannel`: subchannel, where applicable


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
    "traditional-media"
  ],
  "description": "Delivers a better experience by supporting parameter specification.\n\nParameters can be obtained from the official website, for instance:\n\n`https://www.rfa.org/cantonese/news` corresponds to `/rfa/cantonese/news`\n\n`https://www.rfa.org/cantonese/news/htm` corresponds to `/rfa/cantonese/news/htm`",
  "example": "/rfa/english",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 28,
  "location": "index.ts",
  "maintainers": [
    "zphw"
  ],
  "name": "News",
  "parameters": {
    "channel": "channel",
    "language": "language, English by default",
    "subChannel": "subchannel, where applicable"
  },
  "path": "/:language?/:channel?/:subChannel?",
  "topFeeds": [
    {
      "description": "RFA - Powered by RSSHub",
      "errorAt": "2024-12-03T21:52:29.053Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "41511702474276901",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.rfa.org/",
      "title": "RFA",
      "type": "feed",
      "url": "rsshub://rfa/mandarin"
    },
    {
      "description": "RFA - Powered by RSSHub",
      "errorAt": "2024-10-07T20:30:24.636Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "60960710409964544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.rfa.org/",
      "title": "RFA",
      "type": "feed",
      "url": "rsshub://rfa/english"
    }
  ]
}
```
