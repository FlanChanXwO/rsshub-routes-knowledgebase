# The Australian Financial Review - Latest

## Coverage
`index-only`

## Route
- Namespace: `afr`
- Namespace Name: `The Australian Financial Review`
- Route Path: `/afr/latest`
- Route Name: `Latest`
- Example: `/afr/latest`
- URL: `www.afr.com/latest`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `latest.ts`
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
  - `www.afr.com/latest`
  - `www.afr.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/afr/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "latest.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Latest",
  "path": "/latest",
  "radar": [
    {
      "source": [
        "www.afr.com/latest",
        "www.afr.com/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "The latest news, events, analysis and opinion from The Australian Financial Review - Powered by RSSHub",
      "errorAt": "2024-12-02T20:32:17.473Z",
      "errorMessage": "Cannot read properties of undefined (reading 'assetsConnectionByCriteria')\n",
      "id": "80616874570062848",
      "image": "https://www.afr.com/apple-touch-icon-1024x1024.png",
      "ownerUserId": null,
      "siteUrl": "https://www.afr.com/latest",
      "title": "Latest | The Australian Financial Review | AFR",
      "type": "feed",
      "url": "rsshub://afr/latest"
    }
  ],
  "url": "www.afr.com/latest"
}
```
