# CosplayTele - Tag

## Coverage
`index-only`

## Route
- Namespace: `cosplaytele`
- Namespace Name: `CosplayTele`
- Route Path: `/tag/:tag`
- Route Name: `Tag`
- Example: `/cosplaytele/tag/aqua`
- URL: `cosplaytele.com/`
- Language: `en`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/cosplaytele/tag.ts')`

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
  - `cosplaytele.com/tag/:tag`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/cosplaytele/tag/aqua",
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
  "module": "() => import('@/routes/cosplaytele/tag.ts')",
  "name": "Tag",
  "parameters": {
    "tag": "Tag"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "cosplaytele.com/tag/:tag"
      ],
      "target": "/tag/:tag"
    }
  ],
  "url": "cosplaytele.com/"
}
```
