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
  "topFeeds": [
    {
      "description": "Fur Affinity Gallery of oddeyresproductions - Powered by RSSHub",
      "errorAt": "2026-05-25T18:57:48.549Z",
      "errorMessage": "[GET] \"https://faexport.spangle.org.uk/user/oddeyresproductions/gallery.json?full=1\": 500 Internal Server Error\n[GET] \"https://faexport.spangle.org.uk/user/oddeyresproductions/gallery.json?full=1\": 500 Internal Server Error\n",
      "id": "79207337889916928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.furaffinity.net/gallery/oddeyresproductions",
      "title": "Fur Affinity | Gallery of oddeyresproductions",
      "type": "feed",
      "url": "rsshub://furaffinity/art/gallery/oddeyresproductions/nsfw"
    },
    {
      "description": "Fur Affinity Gallery of draxosdragon - Powered by RSSHub",
      "errorAt": "2026-05-25T13:07:39.855Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://faexport.spangle.org.uk/user/draxosdragon/gallery.json?full=1\": 500 Internal Server Error\n",
      "id": "79207933856438272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.furaffinity.net/gallery/draxosdragon",
      "title": "Fur Affinity | Gallery of draxosdragon",
      "type": "feed",
      "url": "rsshub://furaffinity/art/gallery/draxosdragon/nsfw"
    }
  ],
  "url": "furaffinity.net"
}
```
