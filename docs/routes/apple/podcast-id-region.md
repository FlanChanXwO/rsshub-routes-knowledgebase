# Apple - 播客

## Coverage
`index-only`

## Route
- Namespace: `apple`
- Namespace Name: `Apple`
- Route Path: `/podcast/:id/:region?`
- Route Name: `播客`
- Example: `/apple/podcast/id1559695855/cn`
- URL: `www.apple.com/apple-podcasts/`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `Acring`
- Source Location: `podcast.ts`
- Source Module: `() => import('@/routes/apple/podcast.ts')`

## Description
_None_

## Parameters
- `id`: 播客id，可以在 Apple 播客app 内分享的播客的 URL 中找到
- `region`: 地區代碼，例如 cn、us、jp，預設為 cn


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
  - `podcasts.apple.com/:region/podcast/:showName/:id`
  - `podcasts.apple.com/:region/podcast/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/apple/podcast/id1559695855/cn",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "podcast.ts",
  "maintainers": [
    "Acring"
  ],
  "module": "() => import('@/routes/apple/podcast.ts')",
  "name": "播客",
  "parameters": {
    "id": "播客id，可以在 Apple 播客app 内分享的播客的 URL 中找到",
    "region": "地區代碼，例如 cn、us、jp，預設為 cn"
  },
  "path": "/podcast/:id/:region?",
  "radar": [
    {
      "source": [
        "podcasts.apple.com/:region/podcast/:showName/:id",
        "podcasts.apple.com/:region/podcast/:id"
      ]
    }
  ],
  "url": "www.apple.com/apple-podcasts/"
}
```
