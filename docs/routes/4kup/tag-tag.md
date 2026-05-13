# 4KUP - Tag

## Coverage
`index-only`

## Route
- Namespace: `4kup`
- Namespace Name: `4KUP`
- Route Path: `/tag/:tag`
- Route Name: `Tag`
- Example: `/4kup/tag/asian`
- URL: `4kup.net/`
- Language: `en`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/4kup/tag.ts')`

## Description
_None_

## Parameters
- `tag`: Tag


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
  - `4kup.net/tag/:tag`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/4kup/tag/asian",
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
    "AiraNadih"
  ],
  "module": "() => import('@/routes/4kup/tag.ts')",
  "name": "Tag",
  "parameters": {
    "tag": "Tag"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "4kup.net/tag/:tag"
      ],
      "target": "/tag/:tag"
    }
  ],
  "url": "4kup.net/"
}
```
