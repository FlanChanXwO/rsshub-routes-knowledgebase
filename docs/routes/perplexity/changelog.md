# Perplexity - Changelog

## Coverage
`index-only`

## Route
- Namespace: `perplexity`
- Namespace Name: `Perplexity`
- Route Path: `/changelog`
- Route Name: `Changelog`
- Example: `/perplexity/changelog`
- URL: `www.perplexity.ai`
- Language: `en`
- Categories: `program-update`
- Maintainers: `xbot`
- Source Location: `changelog.ts`
- Source Module: `() => import('@/routes/perplexity/changelog.ts')`

## Description
Subscribe to Perplexity changelog for latest updates and releases.

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.perplexity.ai/changelog`
- `target`: `/changelog`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "Subscribe to Perplexity changelog for latest updates and releases.",
  "example": "/perplexity/changelog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "changelog.ts",
  "maintainers": [
    "xbot"
  ],
  "module": "() => import('@/routes/perplexity/changelog.ts')",
  "name": "Changelog",
  "path": "/changelog",
  "radar": [
    {
      "source": [
        "www.perplexity.ai/changelog"
      ],
      "target": "/changelog"
    }
  ],
  "url": "www.perplexity.ai",
  "view": 0
}
```
