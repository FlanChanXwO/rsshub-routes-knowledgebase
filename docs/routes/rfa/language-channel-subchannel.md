# Radio Free Asia (RFA) 自由亚洲电台 - News

## Coverage
`index-only`

## Route
- Namespace: `rfa`
- Namespace Name: `Radio Free Asia (RFA) 自由亚洲电台`
- Route Path: `/:language?/:channel?/:subChannel?`
- Route Name: `News`
- Example: `/rfa/english`
- URL: `rfa.org`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `zphw`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/rfa/index.ts')`

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
  "location": "index.ts",
  "maintainers": [
    "zphw"
  ],
  "module": "() => import('@/routes/rfa/index.ts')",
  "name": "News",
  "parameters": {
    "channel": "channel",
    "language": "language, English by default",
    "subChannel": "subchannel, where applicable"
  },
  "path": "/:language?/:channel?/:subChannel?"
}
```
