# PKMer - 最近更新

## Coverage
`index-only`

## Route
- Namespace: `pkmer`
- Namespace Name: `PKMer`
- Route Path: `/recent`
- Route Name: `最近更新`
- Example: `/pkmer/recent`
- URL: `pkmer.cn/page/*`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `Gnoyong`
- Source Location: `recent.ts`
- Source Module: `() => import('@/routes/pkmer/recent.ts')`

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
  - `pkmer.cn/page/*`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/pkmer/recent",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "recent.ts",
  "maintainers": [
    "Gnoyong"
  ],
  "module": "() => import('@/routes/pkmer/recent.ts')",
  "name": "最近更新",
  "parameters": {},
  "path": "/recent",
  "radar": [
    {
      "source": [
        "pkmer.cn/page/*"
      ]
    }
  ],
  "url": "pkmer.cn/page/*"
}
```
