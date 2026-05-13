# Bandcamp - Tag

## Coverage
`index-only`

## Route
- Namespace: `bandcamp`
- Namespace Name: `Bandcamp`
- Route Path: `/tag/:tag?`
- Route Name: `Tag`
- Example: `/bandcamp/tag/united-kingdom`
- URL: `bandcamp.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/bandcamp/tag.ts')`

## Description
_None_

## Parameters
- `tag`: Tag, can be found in URL


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
  - `bandcamp.com/tag/:tag`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/bandcamp/tag/united-kingdom",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/bandcamp/tag.ts')",
  "name": "Tag",
  "parameters": {
    "tag": "Tag, can be found in URL"
  },
  "path": "/tag/:tag?",
  "radar": [
    {
      "source": [
        "bandcamp.com/tag/:tag"
      ],
      "target": "/tag/:tag"
    }
  ]
}
```
