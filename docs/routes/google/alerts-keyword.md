# Google - Alerts

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/alerts/:keyword`
- Route Name: `Alerts`
- Example: `/google/alerts/RSSHub`
- URL: `www.google.com`
- Language: `en`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `alerts.ts`
- Source Module: `() => import('@/routes/google/alerts.ts')`

## Description
_None_

## Parameters
- `keyword`: Keyword


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
    "other"
  ],
  "example": "/google/alerts/RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "alerts.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/google/alerts.ts')",
  "name": "Alerts",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/alerts/:keyword"
}
```
