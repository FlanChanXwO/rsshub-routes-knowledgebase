# NGOCN - 首页

## Coverage
`index-only`

## Route
- Namespace: `ngocn2`
- Namespace Name: `NGOCN`
- Route Path: `/:category?`
- Route Name: `首页`
- Example: `/ngocn2`
- URL: `ngocn2.org/`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/ngocn2/index.ts')`

## Description
| 所有文章 | 早报        | 热点     |
| -------- | ----------- | -------- |
| article  | daily-brief | trending |

## Parameters
- `category`: 分类，见下表，默认为所有文章


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `ngocn2.org/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 所有文章 | 早报        | 热点     |\n| -------- | ----------- | -------- |\n| article  | daily-brief | trending |",
  "example": "/ngocn2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/ngocn2/index.ts')",
  "name": "首页",
  "parameters": {
    "category": "分类，见下表，默认为所有文章"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "ngocn2.org/"
      ]
    }
  ],
  "url": "ngocn2.org/"
}
```
