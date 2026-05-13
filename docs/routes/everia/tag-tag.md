# EVERIA.CLUB - Images with tag

## Coverage
`index-only`

## Route
- Namespace: `everia`
- Namespace Name: `EVERIA.CLUB`
- Route Path: `/tag/:tag`
- Route Name: `Images with tag`
- Example: `/everia/tag/hinatazaka46-日向坂46`
- URL: `everia.club`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `KTachibanaM, AiraNadih`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/everia/tag.ts')`

## Description
_None_

## Parameters
- `tag`: Tag of the image stream


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
  - `everia.club/tag/:tag`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/everia/tag/hinatazaka46-日向坂46",
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
    "KTachibanaM",
    "AiraNadih"
  ],
  "module": "() => import('@/routes/everia/tag.ts')",
  "name": "Images with tag",
  "parameters": {
    "tag": "Tag of the image stream"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "everia.club/tag/:tag"
      ],
      "target": "/tag/:tag"
    }
  ]
}
```
