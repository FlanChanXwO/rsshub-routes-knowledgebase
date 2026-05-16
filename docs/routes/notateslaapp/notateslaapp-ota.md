# Not a Tesla App - Tesla Software Updates

## Coverage
`index-only`

## Route
- Namespace: `notateslaapp`
- Namespace Name: `Not a Tesla App`
- Route Path: `/notateslaapp/ota`
- Route Name: `Tesla Software Updates`
- Example: `/notateslaapp/ota`
- URL: `notateslaapp.com/software-updates/history`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `mrbruce516`
- Source Location: `update.ts`
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
  - `notateslaapp.com/software-updates/history`
  - `notateslaapp.com/software-updates`
  - `notateslaapp.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/notateslaapp/ota",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "update.ts",
  "maintainers": [
    "mrbruce516"
  ],
  "name": "Tesla Software Updates",
  "parameters": {},
  "path": "/ota",
  "radar": [
    {
      "source": [
        "notateslaapp.com/software-updates/history",
        "notateslaapp.com/software-updates",
        "notateslaapp.com/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "特斯拉系统更新 - 最新发布 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66384857823758336",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.notateslaapp.com/software-updates/history/",
      "title": "特斯拉系统更新",
      "type": "feed",
      "url": "rsshub://notateslaapp/ota"
    }
  ],
  "url": "notateslaapp.com/software-updates/history"
}
```
