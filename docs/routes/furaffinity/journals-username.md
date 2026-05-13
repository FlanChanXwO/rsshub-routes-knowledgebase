# Furaffinity - Journals

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/journals/:username`
- Route Name: `Journals`
- Example: `/furaffinity/journals/fender`
- URL: `furaffinity.net`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `journals.ts`
- Source Module: `() => import('@/routes/furaffinity/journals.ts')`

## Description
_None_

## Parameters
- `username`: Username, can find in userpage


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
  - `furaffinity.net/journals/:username`
- `target`: `/journals/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/journals/fender",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "journals.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "module": "() => import('@/routes/furaffinity/journals.ts')",
  "name": "Journals",
  "parameters": {
    "username": "Username, can find in userpage"
  },
  "path": "/journals/:username",
  "radar": [
    {
      "source": [
        "furaffinity.net/journals/:username"
      ],
      "target": "/journals/:username"
    }
  ],
  "url": "furaffinity.net"
}
```
