# 品葱 - 精选

## Coverage
`index-only`

## Route
- Namespace: `pincong`
- Namespace Name: `品葱`
- Route Path: `/pincong/hot/:category?`
- Route Name: `精选`
- Example: `/pincong/hot`
- URL: `pincong.rocks`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `zphw`
- Source Location: `hot.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分类，与官网分类 URL `category-` 后的数字对应，默认为全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
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
  "example": "/pincong/hot",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 98,
  "location": "hot.ts",
  "maintainers": [
    "zphw"
  ],
  "name": "精选",
  "parameters": {
    "category": "分类，与官网分类 URL `category-` 后的数字对应，默认为全部"
  },
  "path": "/hot/:category?",
  "topFeeds": [
    {
      "description": "品葱 - 精选 - Powered by RSSHub",
      "errorAt": "2026-07-06T03:12:26.422Z",
      "errorMessage": "Could not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nFailed to fetch\nFailed to fetch\nFailed to fetch\n",
      "id": "53908061985105940",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pincong.rocks/hot/",
      "title": "品葱 - 精选",
      "type": "feed",
      "url": "rsshub://pincong/hot"
    }
  ]
}
```
