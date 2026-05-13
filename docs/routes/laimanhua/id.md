# 来漫画 - 漫画列表

## Coverage
`index-only`

## Route
- Namespace: `laimanhua`
- Namespace Name: `来漫画`
- Route Path: `/:id`
- Route Name: `漫画列表`
- Example: `/laimanhua/tiandikangzhanjiVERSUS`
- URL: `www.laimanhua8.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/laimanhua/index.ts')`

## Description
_None_

## Parameters
- `id`: 漫画 ID，可在 URL 中找到


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
  - `www.laimanhua8.com/kanmanhua/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/laimanhua/tiandikangzhanjiVERSUS",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/laimanhua/index.ts')",
  "name": "漫画列表",
  "parameters": {
    "id": "漫画 ID，可在 URL 中找到"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "www.laimanhua8.com/kanmanhua/:id"
      ]
    }
  ]
}
```
