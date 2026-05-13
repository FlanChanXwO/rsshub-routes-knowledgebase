# 乳首ふぇち - Tag

## Coverage
`index-only`

## Route
- Namespace: `chikubi`
- Namespace Name: `乳首ふぇち`
- Route Path: `/tag/:keyword`
- Route Name: `Tag`
- Example: `/chikubi/tag/ドリームチケット`
- URL: `chikubi.jp`
- Language: `ja`
- Categories: `multimedia`
- Maintainers: `SnowAgar25`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/chikubi/tag.ts')`

## Description
_None_

## Parameters
- `keyword`: Keyword


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
- `title`: `Tag`
- `source`:
  - `chikubi.jp/tag/:keyword`
- `target`: `/tag/:keyword`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/chikubi/tag/ドリームチケット",
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
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/chikubi/tag.ts')",
  "name": "Tag",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/tag/:keyword",
  "radar": [
    {
      "source": [
        "chikubi.jp/tag/:keyword"
      ],
      "target": "/tag/:keyword",
      "title": "Tag"
    }
  ]
}
```
