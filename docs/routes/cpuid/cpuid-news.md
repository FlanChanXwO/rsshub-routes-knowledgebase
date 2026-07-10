# CPUID - News

## Coverage
`index-only`

## Route
- Namespace: `cpuid`
- Namespace Name: `CPUID`
- Route Path: `/cpuid/news`
- Route Name: `News`
- Example: `/cpuid/news`
- URL: `cpuid.com/news.html`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `None`
- Source Location: `news.ts`
- Source Module: `_None_`

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
  "heat": 1,
  "location": "news.ts",
  "maintainers": [],
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
  "topFeeds": [
    {
      "description": "News | CPUID - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "197193831829736448",
      "image": "https://www.cpuid.com/medias/images/apple-touch-icon-precomposed.png",
      "ownerUserId": null,
      "siteUrl": "https://www.cpuid.com/news.html",
      "title": "News | CPUID",
      "type": "feed",
      "url": "rsshub://cpuid/news"
    }
  ],
  "url": "cpuid.com/news.html"
}
```
