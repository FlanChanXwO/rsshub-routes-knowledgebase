# Mozilla - Firefox Monitor

## Coverage
`index-only`

## Route
- Namespace: `firefox`
- Namespace Name: `Mozilla`
- Route Path: `/breaches`
- Route Name: `Firefox Monitor`
- Example: `/firefox/breaches`
- URL: `monitor.firefox.com/`
- Language: `en`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `breaches.ts`
- Source Module: `() => import('@/routes/firefox/breaches.ts')`

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
  - `monitor.firefox.com/`
  - `monitor.firefox.com/breaches`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/firefox/breaches",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "breaches.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/firefox/breaches.ts')",
  "name": "Firefox Monitor",
  "parameters": {},
  "path": "/breaches",
  "radar": [
    {
      "source": [
        "monitor.firefox.com/",
        "monitor.firefox.com/breaches"
      ]
    }
  ],
  "url": "monitor.firefox.com/"
}
```
