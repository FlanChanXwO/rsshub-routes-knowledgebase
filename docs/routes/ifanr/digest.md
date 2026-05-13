# 爱范儿 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `ifanr`
- Namespace Name: `爱范儿`
- Route Path: `/digest`
- Route Name: `快讯`
- Example: `/ifanr/digest`
- URL: `www.ifanr.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `digest.ts`
- Source Module: `() => import('@/routes/ifanr/digest.ts')`

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
  - `www.ifanr.comdigest`
- `target`: `/digest`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/ifanr/digest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "digest.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/ifanr/digest.ts')",
  "name": "快讯",
  "path": "/digest",
  "radar": [
    {
      "source": [
        "www.ifanr.comdigest"
      ],
      "target": "/digest"
    }
  ],
  "url": "www.ifanr.com",
  "view": 0
}
```
