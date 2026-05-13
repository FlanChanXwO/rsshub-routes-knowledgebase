# 動漫狂 - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `cartoonmad`
- Namespace Name: `動漫狂`
- Route Path: `/comic/:id`
- Route Name: `漫画更新`
- Example: `/cartoonmad/comic/5827`
- URL: `cartoonmad.com`
- Language: `zh-TW`
- Categories: `anime`
- Maintainers: `KellyHwong`
- Source Location: `comic.tsx`
- Source Module: `() => import('@/routes/cartoonmad/comic.tsx')`

## Description
_None_

## Parameters
- `id`: 漫画ID


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
  - `cartoonmad.com/comic/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/cartoonmad/comic/5827",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "comic.tsx",
  "maintainers": [
    "KellyHwong"
  ],
  "module": "() => import('@/routes/cartoonmad/comic.tsx')",
  "name": "漫画更新",
  "parameters": {
    "id": "漫画ID"
  },
  "path": "/comic/:id",
  "radar": [
    {
      "source": [
        "cartoonmad.com/comic/:id"
      ]
    }
  ]
}
```
