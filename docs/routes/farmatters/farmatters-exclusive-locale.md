# Farmatters - Exclusive

## Coverage
`index-only`

## Route
- Namespace: `farmatters`
- Namespace Name: `Farmatters`
- Route Path: `/farmatters/exclusive/:locale?`
- Route Name: `Exclusive`
- Example: `/farmatters/exclusive`
- URL: `farmatters.com/news`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `locale`: Locale, `zh-CN` or `en-US`, `zh-CN` by default


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
  - `farmatters.com/exclusive`
- `target`: `/exclusive`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/farmatters/exclusive",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Exclusive",
  "parameters": {
    "locale": "Locale, `zh-CN` or `en-US`, `zh-CN` by default"
  },
  "path": [
    "/exclusive/:locale?",
    "/news/:locale?",
    "/:locale?",
    "/:type/:id/:locale?"
  ],
  "radar": [
    {
      "source": [
        "farmatters.com/exclusive"
      ],
      "target": "/exclusive"
    }
  ],
  "topFeeds": [],
  "url": "farmatters.com/news"
}
```
