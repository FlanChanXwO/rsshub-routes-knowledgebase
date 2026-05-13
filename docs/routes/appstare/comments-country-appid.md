# AppStare - Comments

## Coverage
`index-only`

## Route
- Namespace: `appstare`
- Namespace Name: `AppStare`
- Route Path: `/comments/:country/:appid`
- Route Name: `Comments`
- Example: `/appstare/comments/cn/989673964`
- URL: `appstare.net/`
- Language: `zh-CN`
- Categories: `program-update`
- Maintainers: `zhixideyu`
- Source Location: `comments.ts`
- Source Module: `() => import('@/routes/appstare/comments.ts')`

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
  "location": "comments.ts",
  "maintainers": [
    "zhixideyu"
  ],
  "module": "() => import('@/routes/appstare/comments.ts')",
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
  "url": "appstare.net/"
}
```
