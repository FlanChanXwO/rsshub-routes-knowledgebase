# 证券时报网 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `stcn`
- Namespace Name: `证券时报网`
- Route Path: `/article/list/kx`
- Route Name: `快讯`
- Example: `/stcn/article/list/kx`
- URL: `www.stcn.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `kx.ts`
- Source Module: `() => import('@/routes/stcn/kx.ts')`

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
  - `www.stcn.com/article/list/kx.html`
- `target`: `/article/list/kx`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/stcn/article/list/kx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "kx.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/stcn/kx.ts')",
  "name": "快讯",
  "path": "/article/list/kx",
  "radar": [
    {
      "source": [
        "www.stcn.com/article/list/kx.html"
      ],
      "target": "/article/list/kx"
    }
  ],
  "url": "www.stcn.com",
  "view": 0
}
```
