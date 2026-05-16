# Furaffinity - Home

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/furaffinity/home/:category/:mode?`
- Route Name: `Home`
- Example: `/furaffinity/home/nsfw`
- URL: `furaffinity.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `home.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category, default value is artwork, options are artwork, writing, music, crafts
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
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/home/nsfw",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "home.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "name": "Home",
  "parameters": {
    "category": "Category, default value is artwork, options are artwork, writing, music, crafts",
    "mode": "R18 content toggle, default value is sfw, options are sfw, nsfw"
  },
  "path": "/home/:category/:mode?",
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
      "description": "Fur Affinity Index - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78978405973911552",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.furaffinity.net/",
      "title": "Fur Affinity | Home",
      "type": "feed",
      "url": "rsshub://furaffinity/home/nsfw"
    },
    {
      "description": "Fur Affinity Index - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "85914165909319680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.furaffinity.net/",
      "title": "Fur Affinity | Home",
      "type": "feed",
      "url": "rsshub://furaffinity/home/home"
    }
  ],
  "url": "furaffinity.net"
}
```
