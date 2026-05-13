# 蓝点网 - 标签

## Coverage
`index-only`

## Route
- Namespace: `landiannews`
- Namespace Name: `蓝点网`
- Route Path: `/tag/:slug`
- Route Name: `标签`
- Example: `/landiannews/tag/linux-kernel`
- URL: `www.landiannews.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `cscnk52`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/landiannews/tag.ts')`

## Description
_None_

## Parameters
- `slug`: 标签名称


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.landiannews.com/archives/tag/:slug`
- `target`: `/tag/:slug`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/landiannews/tag/linux-kernel",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "cscnk52"
  ],
  "module": "() => import('@/routes/landiannews/tag.ts')",
  "name": "标签",
  "parameters": {
    "slug": "标签名称"
  },
  "path": "/tag/:slug",
  "radar": [
    {
      "source": [
        "www.landiannews.com/archives/tag/:slug"
      ],
      "target": "/tag/:slug"
    }
  ],
  "url": "www.landiannews.com",
  "view": 0
}
```
