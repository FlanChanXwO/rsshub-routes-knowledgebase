# NGOCN - 首页

## Coverage
`index-only`

## Route
- Namespace: `ngocn2`
- Namespace Name: `NGOCN`
- Route Path: `/ngocn2/:category?`
- Route Name: `首页`
- Example: `/ngocn2`
- URL: `ngocn2.org/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

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
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
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
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-08-20T04:17:37.998Z",
      "errorMessage": "[GET] \"https://ngocn2.org/article\": 523 <none>\n",
      "id": "180794735208561664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://ngocn2"
    }
  ],
  "url": "ngocn2.org/"
}
```
