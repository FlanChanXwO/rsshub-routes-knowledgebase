# ScienceDirect - Journal

## Coverage
`index-only`

## Route
- Namespace: `sciencedirect`
- Namespace Name: `ScienceDirect`
- Route Path: `/sciencedirect/journal/:id`
- Route Name: `Journal`
- Example: `/sciencedirect/journal/research-policy`
- URL: `sciencedirect.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `journal.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Journal id, can be found in URL


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
  - `sciencedirect.com/journal/:id`
  - `sciencedirect.com/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/sciencedirect/journal/research-policy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "journal.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Journal",
  "parameters": {
    "id": "Journal id, can be found in URL"
  },
  "path": "/journal/:id",
  "radar": [
    {
      "source": [
        "sciencedirect.com/journal/:id",
        "sciencedirect.com/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-07-13T06:37:53.133Z",
      "errorMessage": "[GET] \"https://www.sciencedirect.com/journal/progress-in-solid-state-chemistry/articles-in-press\": 400 Bad Request\n",
      "id": "167109692329335818",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://sciencedirect/journal/progress-in-solid-state-chemistry"
    }
  ]
}
```
