# AP News - News (from mobile client API)

## Coverage
`index-only`

## Route
- Namespace: `apnews`
- Namespace Name: `AP News`
- Route Path: `/mobile/:path{.+}?`
- Route Name: `News (from mobile client API)`
- Example: `/apnews/mobile/ap-top-news`
- URL: `apnews.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `mobile-api.ts`
- Source Module: `() => import('@/routes/apnews/mobile-api.ts')`

## Description
_None_

## Parameters
- `path`: {"default": "ap-top-news", "description": "Corresponding path from AP News website"}


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
  - `apnews.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/apnews/mobile/ap-top-news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "mobile-api.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/apnews/mobile-api.ts')",
  "name": "News (from mobile client API)",
  "parameters": {
    "path": {
      "default": "ap-top-news",
      "description": "Corresponding path from AP News website"
    }
  },
  "path": "/mobile/:path{.+}?",
  "radar": [
    {
      "source": [
        "apnews.com/"
      ]
    }
  ],
  "view": 0
}
```
