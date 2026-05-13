# 番组放送 - 开播提醒

## Coverage
`index-only`

## Route
- Namespace: `bgmlist`
- Namespace Name: `番组放送`
- Route Path: `/onair/:lang?`
- Route Name: `开播提醒`
- Example: `/bgmlist/onair/zh-Hans`
- URL: `bgmlist.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `x2cf`
- Source Location: `onair.tsx`
- Source Module: `() => import('@/routes/bgmlist/onair.tsx')`

## Description
_None_

## Parameters
- `lang`: 语言


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
  "example": "/bgmlist/onair/zh-Hans",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "onair.tsx",
  "maintainers": [
    "x2cf"
  ],
  "module": "() => import('@/routes/bgmlist/onair.tsx')",
  "name": "开播提醒",
  "parameters": {
    "lang": "语言"
  },
  "path": "/onair/:lang?"
}
```
