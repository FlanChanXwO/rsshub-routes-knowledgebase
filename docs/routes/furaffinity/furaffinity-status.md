# Furaffinity - Status

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/furaffinity/status`
- Route Name: `Status`
- Example: `/furaffinity/status`
- URL: `furaffinity.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `status.ts`
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
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `furaffinity.net`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/status",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "status.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "name": "Status",
  "parameters": {},
  "path": "/status",
  "radar": [
    {
      "source": [
        "furaffinity.net"
      ],
      "target": "/"
    }
  ],
  "topFeeds": [
    {
      "description": "Fur Affinity Status - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "87385847063373824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.furaffinity.net/",
      "title": "Fur Affinity | Status",
      "type": "feed",
      "url": "rsshub://furaffinity/status"
    }
  ],
  "url": "furaffinity.net"
}
```
