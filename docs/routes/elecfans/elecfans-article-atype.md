# 电子发烧友 - 文章

## Coverage
`index-only`

## Route
- Namespace: `elecfans`
- Namespace Name: `电子发烧友`
- Route Path: `/elecfans/article/:atype`
- Route Name: `文章`
- Example: `/elecfans/article/special`
- URL: `www.elecfans.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `tian051011`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `atype`: 需获取文章的类别


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
  - `www.elecfans.com`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/elecfans/article/special",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "article.ts",
  "maintainers": [
    "tian051011"
  ],
  "name": "文章",
  "parameters": {
    "atype": "需获取文章的类别"
  },
  "path": "/article/:atype",
  "radar": [
    {
      "source": [
        "www.elecfans.com"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "elecfans special articles - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "182701002532529152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.elecfans.com/article/special/",
      "title": "elecfans special articles",
      "type": "feed",
      "url": "rsshub://elecfans/article/special"
    }
  ]
}
```
