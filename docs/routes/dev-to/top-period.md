# DEV Community - Top Posts

## Coverage
`index-only`

## Route
- Namespace: `dev.to`
- Namespace Name: `DEV Community`
- Route Path: `/top/:period`
- Route Name: `Top Posts`
- Example: `/dev.to/top/week`
- URL: `dev.to/top`
- Language: `en`
- Categories: `programming`
- Maintainers: `dwemerx, Rjnishant530`
- Source Location: `top.ts`
- Source Module: `() => import('@/routes/dev.to/top.ts')`

## Description
_None_

## Parameters
- `period`: Period (week, month, year, infinity)


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
  - `dev.to/top/:period`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/dev.to/top/week",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "top.ts",
  "maintainers": [
    "dwemerx",
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/dev.to/top.ts')",
  "name": "Top Posts",
  "parameters": {
    "period": "Period (week, month, year, infinity)"
  },
  "path": "/top/:period",
  "radar": [
    {
      "source": [
        "dev.to/top/:period"
      ]
    }
  ],
  "url": "dev.to/top"
}
```
