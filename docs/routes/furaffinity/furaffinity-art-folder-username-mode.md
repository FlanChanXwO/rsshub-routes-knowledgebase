# Furaffinity - Gallery

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/furaffinity/art/:folder/:username/:mode?`
- Route Name: `Gallery`
- Example: `/furaffinity/art/gallery/fender/nsfw`
- URL: `furaffinity.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `art.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: Username, can find in userpage
- `folder`: Image folders, options are gallery, scraps, favorites
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
  - `furaffinity.net/gallery/:username`
- `target`: `/gallery/:username`
### Rule 2
- `source`:
  - `furaffinity.net/scraps/:username`
- `target`: `/scraps/:username`
### Rule 3
- `source`:
  - `furaffinity.net/favorites/:username`
- `target`: `/favorites/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/art/gallery/fender/nsfw",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 62,
  "location": "art.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "name": "Gallery",
  "parameters": {
    "folder": "Image folders, options are gallery, scraps, favorites",
    "mode": "R18 content toggle, default value is sfw, options are sfw, nsfw",
    "username": "Username, can find in userpage"
  },
  "path": "/art/:folder/:username/:mode?",
  "radar": [
    {
      "source": [
        "furaffinity.net/gallery/:username"
      ],
      "target": "/gallery/:username"
    },
    {
      "source": [
        "furaffinity.net/scraps/:username"
      ],
      "target": "/scraps/:username"
    },
    {
      "source": [
        "furaffinity.net/favorites/:username"
      ],
      "target": "/favorites/:username"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Fur Affinity Gallery of oddeyresproductions - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79207337889916928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.furaffinity.net/gallery/oddeyresproductions",
      "title": "Fur Affinity | Gallery of oddeyresproductions",
      "type": "feed",
      "url": "rsshub://furaffinity/art/gallery/oddeyresproductions/nsfw"
    },
    {
      "description": "Fur Affinity Gallery of smellslikejavier - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79208716709173248",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.furaffinity.net/gallery/smellslikejavier",
      "title": "Fur Affinity | Gallery of smellslikejavier",
      "type": "feed",
      "url": "rsshub://furaffinity/art/gallery/smellslikejavier/nsfw"
    }
  ],
  "url": "furaffinity.net"
}
```
