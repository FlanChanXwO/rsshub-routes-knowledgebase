# The Australian Financial Review - Navigation

## Coverage
`index-only`

## Route
- Namespace: `afr`
- Namespace Name: `The Australian Financial Review`
- Route Path: `/afr/navigation/:path{.+}`
- Route Name: `Navigation`
- Example: `/afr/navigation/markets`
- URL: `www.afr.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `navigation.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `path`: Navigation path, can be found in the URL of the page


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
  - `www.afr.com/path*`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/afr/navigation/markets",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "navigation.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Navigation",
  "parameters": {
    "path": "Navigation path, can be found in the URL of the page"
  },
  "path": "/navigation/:path{.+}",
  "radar": [
    {
      "source": [
        "www.afr.com/path*"
      ]
    }
  ],
  "topFeeds": [],
  "url": "www.afr.com"
}
```
