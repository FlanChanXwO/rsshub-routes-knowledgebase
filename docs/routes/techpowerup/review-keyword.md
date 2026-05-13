# TechPowerUp - Reviews

## Coverage
`index-only`

## Route
- Namespace: `techpowerup`
- Namespace Name: `TechPowerUp`
- Route Path: `/review/:keyword?`
- Route Name: `Reviews`
- Example: `/techpowerup/review/amd`
- URL: `www.techpowerup.com/review/`
- Language: `en`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `review.ts`
- Source Module: `() => import('@/routes/techpowerup/review.ts')`

## Description
_None_

## Parameters
- `keyword`: Search Keyword


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
  - `techpowerup.com/review/search`
  - `techpowerup.com/review`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/techpowerup/review/amd",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "review.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/techpowerup/review.ts')",
  "name": "Reviews",
  "parameters": {
    "keyword": "Search Keyword"
  },
  "path": "/review/:keyword?",
  "radar": [
    {
      "source": [
        "techpowerup.com/review/search",
        "techpowerup.com/review"
      ],
      "target": ""
    }
  ],
  "url": "www.techpowerup.com/review/"
}
```
