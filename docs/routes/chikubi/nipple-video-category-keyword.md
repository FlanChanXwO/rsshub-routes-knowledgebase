# 乳首ふぇち - 動画カテゴリー

## Coverage
`index-only`

## Route
- Namespace: `chikubi`
- Namespace Name: `乳首ふぇち`
- Route Path: `/nipple-video-category/:keyword`
- Route Name: `動画カテゴリー`
- Example: `/chikubi/nipple-video-category/cat-nipple-video-god`
- URL: `chikubi.jp`
- Language: `ja`
- Categories: `multimedia`
- Maintainers: `SnowAgar25`
- Source Location: `nipple-video-category.ts`
- Source Module: `() => import('@/routes/chikubi/nipple-video-category.ts')`

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
- `title`: `動画カテゴリー`
- `source`:
  - `chikubi.jp/nipple-video-category/:keyword`
- `target`: `/nipple-video-category/:keyword`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/chikubi/nipple-video-category/cat-nipple-video-god",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "nipple-video-category.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/chikubi/nipple-video-category.ts')",
  "name": "動画カテゴリー",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/nipple-video-category/:keyword",
  "radar": [
    {
      "source": [
        "chikubi.jp/nipple-video-category/:keyword"
      ],
      "target": "/nipple-video-category/:keyword",
      "title": "動画カテゴリー"
    }
  ]
}
```
