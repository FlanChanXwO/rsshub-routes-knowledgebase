# Furaffinity - Browse

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/furaffinity/browse/:mode?`
- Route Name: `Browse`
- Example: `/furaffinity/browse/nsfw`
- URL: `furaffinity.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `browse.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `mode`: R18 content toggle, default value is sfw, options are sfw, nsfw


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `furaffinity.net`
- `target`: `/browse`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/browse/nsfw",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "browse.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "name": "Browse",
  "parameters": {
    "mode": "R18 content toggle, default value is sfw, options are sfw, nsfw"
  },
  "path": "/browse/:mode?",
  "radar": [
    {
      "source": [
        "furaffinity.net"
      ],
      "target": "/browse"
    }
  ],
  "topFeeds": [
    {
      "description": "Fur Affinity Browsing Artwork - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82628918077837312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.furaffinity.net/browse/",
      "title": "Fur Affinity | Browse",
      "type": "feed",
      "url": "rsshub://furaffinity/browse"
    },
    {
      "description": "Fur Affinity Browsing Artwork - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79507670825926656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.furaffinity.net/browse/",
      "title": "Fur Affinity | Browse",
      "type": "feed",
      "url": "rsshub://furaffinity/browse/nsfw"
    }
  ],
  "url": "furaffinity.net"
}
```
