# 爆料公社 - 動態

## Coverage
`index-only`

## Route
- Namespace: `bc3ts`
- Namespace Name: `爆料公社`
- Route Path: `/bc3ts/post/list/:sort?`
- Route Name: `動態`
- Example: `/bc3ts/post/list`
- URL: `web.bc3ts.net`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `list.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `sort`: 排序方式，`1` 為最新，`2` 為熱門，默认為 `1`


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `web.bc3ts.net`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/bc3ts/post/list",
  "features": {
    "antiCrawler": true
  },
  "heat": 4,
  "location": "list.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "動態",
  "parameters": {
    "sort": "排序方式，`1` 為最新，`2` 為熱門，默认為 `1`"
  },
  "path": "/post/list/:sort?",
  "radar": [
    {
      "source": [
        "web.bc3ts.net"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "爆料公社最新動態 - Powered by RSSHub",
      "errorAt": "2025-11-26T17:59:38.721Z",
      "errorMessage": "[GET] \"https://app.bc3ts.net/post/list/v2?limits=20&sort_type=1\": 403 Forbidden\n",
      "id": "59860699815644183",
      "image": "https://img.bc3ts.net/image/web/main/logo-white-new-2023.png",
      "ownerUserId": null,
      "siteUrl": "https://web.bc3ts.net/",
      "title": "爆料公社最新動態",
      "type": "feed",
      "url": "rsshub://bc3ts/post/list"
    },
    {
      "description": "爆料公社熱門動態 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61064457830849536",
      "image": "https://img.bc3ts.net/image/web/main/logo-white-new-2023.png",
      "ownerUserId": null,
      "siteUrl": "https://web.bc3ts.net/",
      "title": "爆料公社熱門動態",
      "type": "feed",
      "url": "rsshub://bc3ts/post/list/2"
    }
  ]
}
```
