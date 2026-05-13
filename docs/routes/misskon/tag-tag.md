# MissKON - Tag

## Coverage
`index-only`

## Route
- Namespace: `misskon`
- Namespace Name: `MissKON`
- Route Path: `/tag/:tag`
- Route Name: `Tag`
- Example: `/misskon/tag/cosplay`
- URL: `misskon.com`
- Language: `en`
- Categories: `picture`
- Maintainers: `Urabartin`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/misskon/tag.ts')`

## Description
_None_

## Parameters
- `tag`: Any tag that exists in MissKon


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
  - `misskon.com/tag/:tag/`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/misskon/tag/cosplay",
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
    "Urabartin"
  ],
  "module": "() => import('@/routes/misskon/tag.ts')",
  "name": "Tag",
  "parameters": {
    "tag": "Any tag that exists in MissKon"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "misskon.com/tag/:tag/"
      ],
      "target": "/tag/:tag"
    }
  ]
}
```
