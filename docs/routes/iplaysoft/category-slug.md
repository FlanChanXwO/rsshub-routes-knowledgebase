# 异次元软件世界 - 分类

## Coverage
`index-only`

## Route
- Namespace: `iplaysoft`
- Namespace Name: `异次元软件世界`
- Route Path: `/category/:slug`
- Route Name: `分类`
- Example: `/iplaysoft/category/system`
- URL: `www.iplaysoft.com`
- Language: `zh-CN`
- Categories: `program-update`
- Maintainers: `cscnk52`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/iplaysoft/category.ts')`

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
  - `www.iplaysoft.com/category/:slug`
- `target`: `/category/:slug`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/iplaysoft/category/system",
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
  "module": "() => import('@/routes/iplaysoft/category.ts')",
  "name": "分类",
  "parameters": {
    "slug": "分类名称"
  },
  "path": "/category/:slug",
  "radar": [
    {
      "source": [
        "www.iplaysoft.com/category/:slug"
      ],
      "target": "/category/:slug"
    }
  ],
  "url": "www.iplaysoft.com",
  "view": 0
}
```
