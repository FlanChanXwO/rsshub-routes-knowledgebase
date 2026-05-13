# WFDF - News

## Coverage
`index-only`

## Route
- Namespace: `wfdf`
- Namespace Name: `WFDF`
- Route Path: `/news`
- Route Name: `News`
- Example: `/wfdf/news`
- URL: `wfdf.sport/news/`
- Language: `en`
- Categories: `sport`
- Maintainers: `HankChow`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/wfdf/news.ts')`

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
  - `wfdf.sport/news/`
  - `wfdf.sport/`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "example": "/wfdf/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "HankChow"
  ],
  "module": "() => import('@/routes/wfdf/news.ts')",
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "wfdf.sport/news/",
        "wfdf.sport/"
      ]
    }
  ],
  "url": "wfdf.sport/news/"
}
```
