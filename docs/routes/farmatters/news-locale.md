# Farmatters - Exclusive

## Coverage
`index-only`

## Route
- Namespace: `farmatters`
- Namespace Name: `Farmatters`
- Route Path: `/news/:locale?`
- Route Name: `Exclusive`
- Example: `/farmatters/exclusive`
- URL: `farmatters.com/news`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/farmatters/index.tsx')`

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
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/farmatters/index.tsx')",
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
  "url": "farmatters.com/news"
}
```
