# コラボカフェ - 标签

## Coverage
`index-only`

## Route
- Namespace: `collabo-cafe`
- Namespace Name: `コラボカフェ`
- Route Path: `/tag/:tag`
- Route Name: `标签`
- Example: `/collabo-cafe/tag/ikebukuro`
- URL: `collabo-cafe.com`
- Language: `ja`
- Categories: `anime`
- Maintainers: `cokemine`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/collabo-cafe/tag.ts')`

## Description
_None_

## Parameters
- `tag`: Tag, refer to the original website (開催地域別)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/collabo-cafe/tag/ikebukuro",
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
    "cokemine"
  ],
  "module": "() => import('@/routes/collabo-cafe/tag.ts')",
  "name": "标签",
  "parameters": {
    "tag": "Tag, refer to the original website (開催地域別)"
  },
  "path": "/tag/:tag"
}
```
