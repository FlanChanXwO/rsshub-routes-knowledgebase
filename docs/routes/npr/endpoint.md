# NPR (National Public Radio) - News

## Coverage
`index-only`

## Route
- Namespace: `npr`
- Namespace Name: `NPR (National Public Radio)`
- Route Path: `/:endpoint?`
- Route Name: `News`
- Example: `/npr/1001`
- URL: `npr.org`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `bennyyip`
- Source Location: `full.ts`
- Source Module: `() => import('@/routes/npr/full.ts')`

## Description
Provide full article RSS for CBC topics.

## Parameters
- `endpoint`: Channel ID, can be found in Official RSS URL, `1001` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Provide full article RSS for CBC topics.",
  "example": "/npr/1001",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "full.ts",
  "maintainers": [
    "bennyyip"
  ],
  "module": "() => import('@/routes/npr/full.ts')",
  "name": "News",
  "parameters": {
    "endpoint": "Channel ID, can be found in Official RSS URL, `1001` by default"
  },
  "path": "/:endpoint?"
}
```
