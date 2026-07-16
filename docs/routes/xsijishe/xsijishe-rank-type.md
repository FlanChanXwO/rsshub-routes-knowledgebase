# 司机社 - 排行榜

## Coverage
`index-only`

## Route
- Namespace: `xsijishe`
- Namespace Name: `司机社`
- Route Path: `/xsijishe/rank/:type`
- Route Name: `排行榜`
- Example: `/xsijishe/rank/weekly`
- URL: `xsijishe.com`
- Language: `_None_`
- Categories: `bbs, popular`
- Maintainers: `akynazh, AiraNadih`
- Source Location: `rank.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "排行榜类型", "options": [{"label": "周榜", "value": "weekly"}, {"label": "月榜", "value": "monthly"}]}


## Features
- `requireConfig`: [{"description": "", "name": "XSIJISHE_COOKIE"}, {"description": "", "name": "XSIJISHE_USER_AGENT"}]
- `requirePuppeteer`: true
- `antiCrawler`: true
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
    "bbs",
    "popular"
  ],
  "example": "/xsijishe/rank/weekly",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "",
        "name": "XSIJISHE_COOKIE"
      },
      {
        "description": "",
        "name": "XSIJISHE_USER_AGENT"
      }
    ],
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4829,
  "location": "rank.ts",
  "maintainers": [
    "akynazh",
    "AiraNadih"
  ],
  "name": "排行榜",
  "parameters": {
    "type": {
      "description": "排行榜类型",
      "options": [
        {
          "label": "周榜",
          "value": "weekly"
        },
        {
          "label": "月榜",
          "value": "monthly"
        }
      ]
    }
  },
  "path": "/rank/:type",
  "topFeeds": [
    {
      "description": "司机社综合周排行榜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41707595233790976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xsijishe.com/portal.php",
      "title": "司机社综合周排行榜",
      "type": "feed",
      "url": "rsshub://xsijishe/rank/weekly"
    },
    {
      "description": "司机社综合月排行榜 - Powered by RSSHub",
      "errorAt": "2026-07-15T05:46:55.054Z",
      "errorMessage": "Failed to fetch\nAuthentication failed. Access denied.\n/xsijishe/rank/monthly\n500 \n[GET] \"https://xsijishe.com/portal.php\": 403 Forbidden\n524 \n[GET] \"https://xsijishe.com/portal.php\": 403 Forbidden\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /home/sbx_user1051/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nFailed to fetch\nFailed to fetch\n500 \nFailed to fetch\nFailed to fetch\n",
      "id": "41511702474276884",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xsijishe.com/portal.php",
      "title": "司机社综合月排行榜",
      "type": "feed",
      "url": "rsshub://xsijishe/rank/monthly"
    }
  ]
}
```
