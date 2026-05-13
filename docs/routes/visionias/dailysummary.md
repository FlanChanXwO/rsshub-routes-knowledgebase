# VisionIAS - Daily News Summary

## Coverage
`index-only`

## Route
- Namespace: `visionias`
- Namespace Name: `VisionIAS`
- Route Path: `/dailySummary`
- Route Name: `Daily News Summary`
- Example: `/visionias/dailySummary`
- URL: `visionias.in`
- Language: `en`
- Categories: `study`
- Maintainers: `Rjnishant530`
- Source Location: `daily-news-summary.ts`
- Source Module: `() => import('@/routes/visionias/daily-news-summary.ts')`

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

## Radar
### Rule 1
- `source`:
  - `visionias.in/current-affairs/upsc-daily-news-summary`
- `target`: `/dailySummary`

## Raw JSON
```json
{
  "example": "/visionias/dailySummary",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "daily-news-summary.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/visionias/daily-news-summary.ts')",
  "name": "Daily News Summary",
  "path": "/dailySummary",
  "radar": [
    {
      "source": [
        "visionias.in/current-affairs/upsc-daily-news-summary"
      ],
      "target": "/dailySummary"
    }
  ]
}
```
