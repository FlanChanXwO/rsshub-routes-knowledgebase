# Zuvio - 校園話題

## Coverage
`index-only`

## Route
- Namespace: `zuvio`
- Namespace Name: `Zuvio`
- Route Path: `/student5/:board?`
- Route Name: `校園話題`
- Example: `/zuvio/student5/34`
- URL: `irs.zuvio.com.tw`
- Language: `zh-TW`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `student5.ts`
- Source Module: `() => import('@/routes/zuvio/student5.ts')`

## Description
_None_

## Parameters
- `board`: 看板 ID，空为全站文章，可在看板 URL 或下方路由找到


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
    "bbs"
  ],
  "example": "/zuvio/student5/34",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "student5.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/zuvio/student5.ts')",
  "name": "校園話題",
  "parameters": {
    "board": "看板 ID，空为全站文章，可在看板 URL 或下方路由找到"
  },
  "path": "/student5/:board?"
}
```
