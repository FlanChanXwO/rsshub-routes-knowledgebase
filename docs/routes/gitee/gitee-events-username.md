# Gitee - 用户公开动态

## Coverage
`index-only`

## Route
- Namespace: `gitee`
- Namespace Name: `Gitee`
- Route Path: `/gitee/events/:username`
- Route Name: `用户公开动态`
- Example: `/gitee/events/y_project`
- URL: `gitee.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `users/events.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: 用户名


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
  - `gitee.com/:username`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gitee/events/y_project",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "users/events.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "用户公开动态",
  "parameters": {
    "username": "用户名"
  },
  "path": "/events/:username",
  "radar": [
    {
      "source": [
        "gitee.com/:username"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "callmer - 公开动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "158419992977388544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gitee.com/callmer",
      "title": "callmer - 公开动态",
      "type": "feed",
      "url": "rsshub://gitee/events/callmer"
    },
    {
      "description": "NanGePlus - 公开动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "163616006553730048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gitee.com/NanGePlus",
      "title": "NanGePlus - 公开动态",
      "type": "feed",
      "url": "rsshub://gitee/events/NanGePlus"
    }
  ]
}
```
