# 公視新聞網 - 專題策展

## Coverage
`index-only`

## Route
- Namespace: `pts`
- Namespace Name: `公視新聞網`
- Route Path: `/curations`
- Route Name: `專題策展`
- Example: `/pts/curations`
- URL: `news.pts.org.tw/curations`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `curations.ts`
- Source Module: `() => import('@/routes/pts/curations.ts')`

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
  - `news.pts.org.tw/curations`
  - `news.pts.org.tw/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/pts/curations",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "curations.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/pts/curations.ts')",
  "name": "專題策展",
  "parameters": {},
  "path": "/curations",
  "radar": [
    {
      "source": [
        "news.pts.org.tw/curations",
        "news.pts.org.tw/"
      ]
    }
  ],
  "url": "news.pts.org.tw/curations"
}
```
