# Link3 - Link3 Profile

## Coverage
`index-only`

## Route
- Namespace: `link3`
- Namespace Name: `Link3`
- Route Path: `/link3/profile/:handle`
- Route Name: `Link3 Profile`
- Example: `/link3/profile/synfutures_defi`
- URL: `link3.to`
- Language: `_None_`
- Categories: `other`
- Maintainers: `cxheng315`
- Source Location: `profile.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `handle`: Profile handle


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
  - `link3.to/:handle`
- `target`: `/:handle`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/link3/profile/synfutures_defi",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "profile.ts",
  "maintainers": [
    "cxheng315"
  ],
  "name": "Link3 Profile",
  "parameters": {
    "handle": "Profile handle"
  },
  "path": "/profile/:handle",
  "radar": [
    {
      "source": [
        "link3.to/:handle"
      ],
      "target": "/:handle"
    }
  ],
  "topFeeds": [],
  "url": "link3.to"
}
```
