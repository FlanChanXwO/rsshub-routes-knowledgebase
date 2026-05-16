# 社科期刊网 - 社会学研究

## Coverage
`index-only`

## Route
- Namespace: `ajcass`
- Namespace Name: `社科期刊网`
- Route Path: `/ajcass/shxyj/:year?/:issue?`
- Route Name: `社会学研究`
- Example: `/ajcass/shxyj/2024/1`
- URL: `ajcass.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `CNYoki`
- Source Location: `shxyj.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `year`: Year of the issue, `null` for the lastest
- `issue`: Issue number, `null` for the lastest


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/ajcass/shxyj/2024/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 130,
  "location": "shxyj.ts",
  "maintainers": [
    "CNYoki"
  ],
  "name": "社会学研究",
  "parameters": {
    "issue": "Issue number, `null` for the lastest",
    "year": "Year of the issue, `null` for the lastest"
  },
  "path": "/shxyj/:year?/:issue?",
  "topFeeds": [
    {
      "description": "社会学研究 2026年第2期 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83506691980410880",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://shxyj.ajcass.com/Magazine/?Year=2026&Issue=2",
      "title": "社会学研究 2026年第2期",
      "type": "feed",
      "url": "rsshub://ajcass/shxyj"
    },
    {
      "description": "社会学研究 2024年第1期 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82998945824254976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://shxyj.ajcass.com/Magazine/?Year=2024&Issue=1",
      "title": "社会学研究 2024年第1期",
      "type": "feed",
      "url": "rsshub://ajcass/shxyj/2024/1"
    }
  ]
}
```
