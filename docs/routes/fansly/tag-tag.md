# Fansly - Hashtag

## Coverage
`index-only`

## Route
- Namespace: `fansly`
- Namespace Name: `Fansly`
- Route Path: `/tag/:tag`
- Route Name: `Hashtag`
- Example: `/fansly/tag/free`
- URL: `fansly.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/fansly/tag.ts')`

## Description
_None_

## Parameters
- `tag`: Hashtag


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `fansly.com/explore/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/fansly/tag/free",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/fansly/tag.ts')",
  "name": "Hashtag",
  "parameters": {
    "tag": "Hashtag"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "fansly.com/explore/tag/:tag"
      ]
    }
  ]
}
```
