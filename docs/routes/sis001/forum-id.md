# 第一会所 - 子版块

## Coverage
`index-only`

## Route
- Namespace: `sis001`
- Namespace Name: `第一会所`
- Route Path: `/forum/:id?`
- Route Name: `子版块`
- Example: `/sis001/forum/322`
- URL: `sis001.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `forum.ts`
- Source Module: `() => import('@/routes/sis001/forum.ts')`

## Description
_None_

## Parameters
- `id`: 子版块 ID，可在子论坛 URL 找到，默认为 `Funny Jokes | 短篇笑话区`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/sis001/forum/322",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "forum.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/sis001/forum.ts')",
  "name": "子版块",
  "parameters": {
    "id": "子版块 ID，可在子论坛 URL 找到，默认为 `Funny Jokes | 短篇笑话区`"
  },
  "path": "/forum/:id?"
}
```
