# 蓝点网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `landiannews`
- Namespace Name: `蓝点网`
- Route Path: `/category/:slug`
- Route Name: `分类`
- Example: `/landiannews/category/sells`
- URL: `www.landiannews.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `cscnk52`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/landiannews/category.ts')`

## Description
_None_

## Parameters
- `slug`: 分类名称


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
  - `www.landiannews.com/:slug`
- `target`: `/category/:slug`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/landiannews/category/sells",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "category.ts",
  "maintainers": [
    "cscnk52"
  ],
  "module": "() => import('@/routes/landiannews/category.ts')",
  "name": "分类",
  "parameters": {
    "slug": "分类名称"
  },
  "path": "/category/:slug",
  "radar": [
    {
      "source": [
        "www.landiannews.com/:slug"
      ],
      "target": "/category/:slug"
    }
  ],
  "url": "www.landiannews.com",
  "view": 0
}
```
