# Rattibha - User Threads

## Coverage
`index-only`

## Route
- Namespace: `rattibha`
- Namespace Name: `Rattibha`
- Route Path: `/rattibha/user/:user`
- Route Name: `User Threads`
- Example: `/rattibha/user/elonmusk`
- URL: `rattibha.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `yshalsager`
- Source Location: `user.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: Twitter username, without @


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
  - `rattibha.com/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/rattibha/user/elonmusk",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "user.tsx",
  "maintainers": [
    "yshalsager"
  ],
  "name": "User Threads",
  "parameters": {
    "user": "Twitter username, without @"
  },
  "path": "/user/:user",
  "radar": [
    {
      "source": [
        "rattibha.com/:user"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "سلاسل تغريدات elonmusk - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "147096924904794112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://rattibha.com/elonmusk",
      "title": "سلاسل تغريدات elonmusk",
      "type": "feed",
      "url": "rsshub://rattibha/user/elonmusk"
    }
  ]
}
```
