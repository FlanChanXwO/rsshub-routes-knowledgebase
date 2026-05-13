# Google - News

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/news/:category/:locale`
- Route Name: `News`
- Example: `/google/news/Top stories/hl=en-US&gl=US&ceid=US:en`
- URL: `www.google.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `zoenglinghou, pseudoyu`
- Source Location: `news.tsx`
- Source Module: `() => import('@/routes/google/news.tsx')`

## Description
_None_

## Parameters
- `category`: Category Title
- `locale`: locales, could be found behind `?`, including `hl`, `gl`, and `ceid` as parameters


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/google/news/Top stories/hl=en-US&gl=US&ceid=US:en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.tsx",
  "maintainers": [
    "zoenglinghou",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/google/news.tsx')",
  "name": "News",
  "parameters": {
    "category": "Category Title",
    "locale": "locales, could be found behind `?`, including `hl`, `gl`, and `ceid` as parameters"
  },
  "path": "/news/:category/:locale"
}
```
