# 少数派 sspai - 作者动态

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/sspai/activity/:slug`
- Route Name: `作者动态`
- Example: `/sspai/activity/urfp0d9i`
- URL: `sspai.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `umm233`
- Source Location: `activity.ts`
- Source Module: `_None_`

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
  "heat": 177,
  "location": "activity.ts",
  "maintainers": [
    "umm233"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "少数派用户「玉树芝兰」的动态更新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58311597468054534",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/u/a5xddvxl/updates",
      "title": "少数派用户「玉树芝兰」动态更新",
      "type": "feed",
      "url": "rsshub://sspai/activity/a5xddvxl"
    },
    {
      "description": "少数派用户「西郊次生林」的动态更新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "143174175969882112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/u/05c3mst0/updates",
      "title": "少数派用户「西郊次生林」动态更新",
      "type": "feed",
      "url": "rsshub://sspai/activity/05c3mst0"
    }
  ]
}
```
