# Oxford University Press - Oxford Academic - Journal

## Coverage
`index-only`

## Route
- Namespace: `oup`
- Namespace Name: `Oxford University Press`
- Route Path: `/oup/journals/:name`
- Route Name: `Oxford Academic - Journal`
- Example: `/oup/journals/adaptation`
- URL: `academic.oup.com/`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `Fatpandac`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: short name for a journal, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `academic.oup.com/`
  - `academic.oup.com/:name/issue`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/oup/journals/adaptation",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 47,
  "location": "index.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "Oxford Academic - Journal",
  "parameters": {
    "name": "short name for a journal, can be found in URL"
  },
  "path": "/journals/:name",
  "radar": [
    {
      "source": [
        "academic.oup.com/",
        "academic.oup.com/:name/issue"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "OUP - qje - Powered by RSSHub",
      "errorAt": "2025-07-18T11:52:23.943Z",
      "errorMessage": "Failed to fetch\n",
      "id": "73541899125060608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://academic.oup.com/qje/issue",
      "title": "OUP - qje",
      "type": "feed",
      "url": "rsshub://oup/journals/qje"
    },
    {
      "description": "OUP - adaptation - Powered by RSSHub",
      "errorAt": "2025-07-18T10:38:49.798Z",
      "errorMessage": "[GET] \"https://academic.oup.com/adaptation/issue\": 403 Forbidden\n",
      "id": "150382870590088192",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://academic.oup.com/adaptation/issue",
      "title": "OUP - adaptation",
      "type": "feed",
      "url": "rsshub://oup/journals/adaptation"
    }
  ],
  "url": "academic.oup.com/"
}
```
