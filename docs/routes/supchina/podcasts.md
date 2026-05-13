# SupChina - Podcasts

## Coverage
`index-only`

## Route
- Namespace: `supchina`
- Namespace Name: `SupChina`
- Route Path: `/podcasts`
- Route Name: `Podcasts`
- Example: `/supchina/podcasts`
- URL: `supchina.com/podcasts`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `podcasts.ts`
- Source Module: `() => import('@/routes/supchina/podcasts.ts')`

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
  - `supchina.com/podcasts`
  - `supchina.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/supchina/podcasts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "podcasts.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/supchina/podcasts.ts')",
  "name": "Podcasts",
  "parameters": {},
  "path": "/podcasts",
  "radar": [
    {
      "source": [
        "supchina.com/podcasts",
        "supchina.com/"
      ]
    }
  ],
  "url": "supchina.com/podcasts"
}
```
