# 哔哩哔哩 bilibili - 热搜

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/hot-search`
- Route Name: `热搜`
- Example: `/bilibili/hot-search`
- URL: `www.bilibili.com/`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `CaoMeiYouRen`
- Source Location: `hot-search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `www.bilibili.com/`
### Rule 2
- `source`:
  - `m.bilibili.com/`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/hot-search",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 280,
  "location": "hot-search.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "热搜",
  "parameters": {},
  "path": "/hot-search",
  "radar": [
    {
      "source": [
        "www.bilibili.com/"
      ]
    },
    {
      "source": [
        "m.bilibili.com/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "bilibili热搜 - Powered by RSSHub",
      "errorAt": "2026-05-30T10:53:56.573Z",
      "errorMessage": "Failed to fetch\nFailed to fetch\n[GET] \"https://api.bilibili.com/x/web-interface/nav\": <no response> fetch failed\nbrowserType.connect: WebSocket error: getaddrinfo ENOTFOUND browserless\nCall log:\n  - <ws connecting> ws://browserless:3000/\n  - <ws error> ws://browserless:3000/ error getaddrinfo ENOTFOUND browserless\n  - <ws connect error> ws://browserless:3000/ getaddrinfo ENOTFOUND browserless\n  - <ws disconnected> ws://browserless:3000/ code=1006 reason=\n\n[GET] \"https://api.bilibili.com/x/web-interface/wbi/search/square?limit=10&platform=web&w_rid=eabd76dd5b38cfb6d7b5f21c799a0038&wts=1780192243\": <no response> fetch failed\n",
      "id": "54831663495804928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://api.bilibili.com/x/web-interface/wbi/search/square?limit=10&platform=web&w_rid=1d32dab8ed45d5924937bb46a0f147ab&wts=1780127975",
      "title": "bilibili热搜",
      "type": "feed",
      "url": "rsshub://bilibili/hot-search"
    }
  ],
  "url": "www.bilibili.com/"
}
```
