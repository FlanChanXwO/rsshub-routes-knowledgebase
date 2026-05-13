# 丁香园 - 专题

## Coverage
`index-only`

## Route
- Namespace: `dxy`
- Namespace Name: `丁香园`
- Route Path: `/bbs/special/:specialId`
- Route Name: `专题`
- Example: `/dxy/bbs/special/72`
- URL: `dxy.cn`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `special.ts`
- Source Module: `() => import('@/routes/dxy/special.ts')`

## Description
_None_

## Parameters
- `specialId`: 专题 ID，可在对应专题页 URL 中找到


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
  "example": "/dxy/bbs/special/72",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "special.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/dxy/special.ts')",
  "name": "专题",
  "parameters": {
    "specialId": "专题 ID，可在对应专题页 URL 中找到"
  },
  "path": "/bbs/special/:specialId"
}
```
