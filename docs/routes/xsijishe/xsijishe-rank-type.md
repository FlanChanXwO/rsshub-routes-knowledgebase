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
  "heat": 4817,
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
      "errorAt": "2026-05-29T11:20:13.854Z",
      "errorMessage": "200 OK",
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
      "errorAt": "2026-05-22T21:49:49.069Z",
      "errorMessage": "Failed to fetch\n524 Receive timeout from origin\n[GET] \"https://xsijishe.com/portal.php\": 403 Forbidden\n500 Internal Server Error\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /home/sbx_user1051/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nbrowserType.connect: WebSocket error: getaddrinfo ENOTFOUND browserless\nCall log:\n  - <ws connecting> ws://browserless:3000/\n  - <ws error> ws://browserless:3000/ error getaddrinfo ENOTFOUND browserless\n  - <ws connect error> ws://browserless:3000/ getaddrinfo ENOTFOUND browserless\n  - <ws disconnected> ws://browserless:3000/ code=1006 reason=\n\n[GET] \"https://xsijishe.com/portal.php\": 403 Forbidden\nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
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
