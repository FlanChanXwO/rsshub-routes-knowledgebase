# 裏垢女子まとめ - User

## Coverage
`index-only`

## Route
- Namespace: `uraaka-joshi`
- Namespace Name: `裏垢女子まとめ`
- Route Path: `/:id`
- Route Name: `User`
- Example: `/uraaka-joshi/_rrwq`
- URL: `uraaka-joshi.com/`
- Language: `ja`
- Categories: `other`
- Maintainers: `SettingDust, Halcao`
- Source Location: `uraaka-joshi-user.ts`
- Source Module: `() => import('@/routes/uraaka-joshi/uraaka-joshi-user.ts')`

## Description
_None_

## Parameters
- `id`: User ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `uraaka-joshi.com/:id`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/uraaka-joshi/_rrwq",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "uraaka-joshi-user.ts",
  "maintainers": [
    "SettingDust",
    "Halcao"
  ],
  "module": "() => import('@/routes/uraaka-joshi/uraaka-joshi-user.ts')",
  "name": "User",
  "parameters": {
    "id": "User ID"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "uraaka-joshi.com/:id"
      ]
    }
  ],
  "url": "uraaka-joshi.com/"
}
```
