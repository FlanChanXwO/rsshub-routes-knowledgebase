# 财新博客 - 财新数据通

## Coverage
`index-only`

## Route
- Namespace: `caixin`
- Namespace Name: `财新博客`
- Route Path: `/database`
- Route Name: `财新数据通`
- Example: `/caixin/database`
- URL: `k.caixin.com/web`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `database.ts`
- Source Module: `() => import('@/routes/caixin/database.ts')`

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
  - `k.caixin.com/web`
  - `k.caixin.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/caixin/database",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "database.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/caixin/database.ts')",
  "name": "财新数据通",
  "parameters": {},
  "path": "/database",
  "radar": [
    {
      "source": [
        "k.caixin.com/web",
        "k.caixin.com/"
      ]
    }
  ],
  "url": "k.caixin.com/web"
}
```
