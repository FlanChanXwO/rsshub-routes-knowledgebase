# Nintendo - News（Hong Kong only）

## Coverage
`index-only`

## Route
- Namespace: `nintendo`
- Namespace Name: `Nintendo`
- Route Path: `/news`
- Route Name: `News（Hong Kong only）`
- Example: `/nintendo/news`
- URL: `nintendo.com.hk/topics`
- Language: `en`
- Categories: `game`
- Maintainers: `HFO4`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/nintendo/news.ts')`

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
  - `nintendo.com.hk/topics`
  - `nintendo.com.hk/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/nintendo/news",
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
    "HFO4"
  ],
  "module": "() => import('@/routes/nintendo/news.ts')",
  "name": "News（Hong Kong only）",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "nintendo.com.hk/topics",
        "nintendo.com.hk/"
      ]
    }
  ],
  "url": "nintendo.com.hk/topics"
}
```
