# 中文成人文學網 - 短篇

## Coverage
`index-only`

## Route
- Namespace: `xbookcn`
- Namespace Name: `中文成人文學網`
- Route Path: `/:label?`
- Route Name: `短篇`
- Example: `/xbookcn/精选作品`
- URL: `www.xbookcn.net`
- Language: `zh-TW`
- Categories: `reading`
- Maintainers: `Lyunvy`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/xbookcn/blog.ts')`

## Description
_None_

## Parameters
- `label`: 按名称分类，详见https://blog.xbookcn.net/p/all.html


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
    "reading"
  ],
  "example": "/xbookcn/精选作品",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blog.ts",
  "maintainers": [
    "Lyunvy"
  ],
  "module": "() => import('@/routes/xbookcn/blog.ts')",
  "name": "短篇",
  "parameters": {
    "label": "按名称分类，详见https://blog.xbookcn.net/p/all.html"
  },
  "path": "/:label?"
}
```
