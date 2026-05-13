# iwara - Ranking

## Coverage
`index-only`

## Route
- Namespace: `iwara`
- Namespace Name: `iwara`
- Route Path: `/ranking/:type?/:sort?/:rating?`
- Route Name: `Ranking`
- Example: `/iwara/ranking/video/date/ecchi`
- URL: `www.iwara.tv`
- Language: `en`
- Categories: `None`
- Maintainers: `CaoMeiYouRen233`
- Source Location: `ranking.ts`
- Source Module: `() => import('@/routes/iwara/ranking.ts')`

## Description
_None_

## Parameters
- `type`: Content type, can be video or image, default is video
- `sort`: Sort type, can be date, trending, popularity, views, likes, default is date
- `rating`: Rating, can be all, general, ecchi, default is ecchi


## Features
- `requirePuppeteer`: true
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.iwara.tv/videos`
  - `www.iwara.tv/images`

## Raw JSON
```json
{
  "example": "/iwara/ranking/video/date/ecchi",
  "features": {
    "nsfw": true,
    "requirePuppeteer": true
  },
  "location": "ranking.ts",
  "maintainers": [
    "CaoMeiYouRen233"
  ],
  "module": "() => import('@/routes/iwara/ranking.ts')",
  "name": "Ranking",
  "parameters": {
    "rating": "Rating, can be all, general, ecchi, default is ecchi",
    "sort": "Sort type, can be date, trending, popularity, views, likes, default is date",
    "type": "Content type, can be video or image, default is video"
  },
  "path": "/ranking/:type?/:sort?/:rating?",
  "radar": [
    {
      "source": [
        "www.iwara.tv/videos",
        "www.iwara.tv/images"
      ]
    }
  ]
}
```
