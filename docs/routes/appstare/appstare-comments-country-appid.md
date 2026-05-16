# AppStare - Comments

## Coverage
`index-only`

## Route
- Namespace: `appstare`
- Namespace Name: `AppStare`
- Route Path: `/appstare/comments/:country/:appid`
- Route Name: `Comments`
- Example: `/appstare/comments/cn/989673964`
- URL: `appstare.net/`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `zhixideyu`
- Source Location: `comments.ts`
- Source Module: `_None_`

## Description
Retrieve only the comments of the app from the past 7 days.

## Parameters
- `country`: App Store country code, e.g., US, CN
- `appid`: Unique App Store application identifier (app id)


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
  - `appstare.net/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "Retrieve only the comments of the app from the past 7 days.",
  "example": "/appstare/comments/cn/989673964",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "comments.ts",
  "maintainers": [
    "zhixideyu"
  ],
  "name": "Comments",
  "parameters": {
    "appid": "Unique App Store application identifier (app id)",
    "country": "App Store country code, e.g., US, CN"
  },
  "path": "/comments/:country/:appid",
  "radar": [
    {
      "source": [
        "appstare.net/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "App Comments - Powered by RSSHub",
      "errorAt": "2025-02-12T02:37:00.472Z",
      "errorMessage": "Failed to fetch\n",
      "id": "74324191601785856",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://appstare.net/data/app/comment/989673964/cn",
      "title": "App Comments",
      "type": "feed",
      "url": "rsshub://appstare/comments/cn/989673964"
    }
  ],
  "url": "appstare.net/"
}
```
