# 乳首ふぇち - AVメーカー

## Coverage
`index-only`

## Route
- Namespace: `chikubi`
- Namespace Name: `乳首ふぇち`
- Route Path: `/nipple-video-maker/:keyword`
- Route Name: `AVメーカー`
- Example: `/chikubi/nipple-video-maker/nipple-video-maker-nh`
- URL: `chikubi.jp`
- Language: `ja`
- Categories: `multimedia`
- Maintainers: `SnowAgar25`
- Source Location: `nipple-video-maker.ts`
- Source Module: `() => import('@/routes/chikubi/nipple-video-maker.ts')`

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
- `title`: `AVメーカー`
- `source`:
  - `chikubi.jp/nipple-video-maker/:keyword`
- `target`: `/nipple-video-maker/:keyword`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/chikubi/nipple-video-maker/nipple-video-maker-nh",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "nipple-video-maker.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/chikubi/nipple-video-maker.ts')",
  "name": "AVメーカー",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/nipple-video-maker/:keyword",
  "radar": [
    {
      "source": [
        "chikubi.jp/nipple-video-maker/:keyword"
      ],
      "target": "/nipple-video-maker/:keyword",
      "title": "AVメーカー"
    }
  ]
}
```
