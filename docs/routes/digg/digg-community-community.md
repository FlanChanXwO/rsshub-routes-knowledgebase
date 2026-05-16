# Digg - Community Posts

## Coverage
`index-only`

## Route
- Namespace: `digg`
- Namespace Name: `Digg`
- Route Path: `/digg/community/:community`
- Route Name: `Community Posts`
- Example: `/digg/community/askdigg`
- URL: `digg.com/`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `community.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `community`: Community slug, can be found in the URL


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
  - `digg.com/:community`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/digg/community/askdigg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "community.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Community Posts",
  "parameters": {
    "community": "Community slug, can be found in the URL"
  },
  "path": "/community/:community",
  "radar": [
    {
      "source": [
        "digg.com/:community"
      ]
    }
  ],
  "topFeeds": [],
  "url": "digg.com/"
}
```
