# Bluesky (bsky) - Keywords

## Coverage
`index-only`

## Route
- Namespace: `bsky`
- Namespace Name: `Bluesky (bsky)`
- Route Path: `/keyword/:keyword`
- Route Name: `Keywords`
- Example: `/bsky/keyword/hello`
- URL: `bsky.app`
- Language: `en`
- Categories: `social-media`
- Maintainers: `untitaker, DIYgod`
- Source Location: `keyword.ts`
- Source Module: `() => import('@/routes/bsky/keyword.ts')`

## Description
_None_

## Parameters
- `keyword`: N


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
    "social-media"
  ],
  "example": "/bsky/keyword/hello",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "keyword.ts",
  "maintainers": [
    "untitaker",
    "DIYgod"
  ],
  "module": "() => import('@/routes/bsky/keyword.ts')",
  "name": "Keywords",
  "parameters": {
    "keyword": "N"
  },
  "path": "/keyword/:keyword"
}
```
