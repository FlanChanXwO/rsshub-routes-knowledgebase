# TikTok - User

## Coverage
`index-only`

## Route
- Namespace: `tiktok`
- Namespace Name: `TikTok`
- Route Path: `/tiktok/user/:user/:iframe?`
- Route Name: `User`
- Example: `/tiktok/user/@linustech/true`
- URL: `tiktok.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: User ID, including @
- `iframe`: Use the official iframe to embed the video, which allows you to view the video if the default option does not work. Default to `false`


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.tiktok.com/:user`
- `target`: `/user/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/tiktok/user/@linustech/true",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User",
  "parameters": {
    "iframe": "Use the official iframe to embed the video, which allows you to view the video if the default option does not work. Default to `false`",
    "user": "User ID, including @"
  },
  "path": "/user/:user/:iframe?",
  "radar": [
    {
      "source": [
        "www.tiktok.com/:user"
      ],
      "target": "/user/:user"
    }
  ],
  "topFeeds": []
}
```
