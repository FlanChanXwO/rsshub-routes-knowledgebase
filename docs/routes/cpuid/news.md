# CPUID - News

## Coverage
`index-only`

## Route
- Namespace: `cpuid`
- Namespace Name: `CPUID`
- Route Path: `/news`
- Route Name: `News`
- Example: `/cpuid/news`
- URL: `cpuid.com/news.html`
- Language: `en`
- Categories: `program-update`
- Maintainers: `None`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/cpuid/news.ts')`

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
  - `cpuid.com/news.html`
  - `cpuid.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/cpuid/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [],
  "module": "() => import('@/routes/cpuid/news.ts')",
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "cpuid.com/news.html",
        "cpuid.com/"
      ]
    }
  ],
  "url": "cpuid.com/news.html"
}
```
