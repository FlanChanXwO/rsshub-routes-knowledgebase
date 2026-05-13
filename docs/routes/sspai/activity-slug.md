# 少数派 sspai - 作者动态

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/activity/:slug`
- Route Name: `作者动态`
- Example: `/sspai/activity/urfp0d9i`
- URL: `sspai.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `umm233`
- Source Location: `activity.ts`
- Source Module: `() => import('@/routes/sspai/activity.ts')`

## Description
_None_

## Parameters
- `slug`: 作者 slug，可在作者主页URL中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `sspai.com/u/:id/updates`
- `target`: `/activity/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/activity/urfp0d9i",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "activity.ts",
  "maintainers": [
    "umm233"
  ],
  "module": "() => import('@/routes/sspai/activity.ts')",
  "name": "作者动态",
  "parameters": {
    "slug": "作者 slug，可在作者主页URL中找到"
  },
  "path": "/activity/:slug",
  "radar": [
    {
      "source": [
        "sspai.com/u/:id/updates"
      ],
      "target": "/activity/:id"
    }
  ]
}
```
