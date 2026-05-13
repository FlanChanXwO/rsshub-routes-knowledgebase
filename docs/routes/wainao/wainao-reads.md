# 歪脑 - 歪脑读

## Coverage
`index-only`

## Route
- Namespace: `wainao`
- Namespace Name: `歪脑`
- Route Path: `/wainao-reads`
- Route Name: `歪脑读`
- Example: `/wainao/wainao-reads`
- URL: `www.wainao.me`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `lucky13820`
- Source Location: `wainao-reads.ts`
- Source Module: `() => import('@/routes/wainao/wainao-reads.ts')`

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
  - `www.wainao.me`
  - `www.wainao.me/wainao-reads`
- `target`: `/wainao-reads`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/wainao/wainao-reads",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "wainao-reads.ts",
  "maintainers": [
    "lucky13820"
  ],
  "module": "() => import('@/routes/wainao/wainao-reads.ts')",
  "name": "歪脑读",
  "path": "/wainao-reads",
  "radar": [
    {
      "source": [
        "www.wainao.me",
        "www.wainao.me/wainao-reads"
      ],
      "target": "/wainao-reads"
    }
  ],
  "url": "www.wainao.me"
}
```
