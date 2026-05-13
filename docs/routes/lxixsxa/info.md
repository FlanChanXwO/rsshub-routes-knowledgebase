# LiSA - News

## Coverage
`index-only`

## Route
- Namespace: `lxixsxa`
- Namespace Name: `LiSA`
- Route Path: `/info`
- Route Name: `News`
- Example: `/lxixsxa/info`
- URL: `www.lxixsxa.com/`
- Language: `ja`
- Categories: `live`
- Maintainers: `Kiotlin`
- Source Location: `information.tsx`
- Source Module: `() => import('@/routes/lxixsxa/information.tsx')`

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
  - `www.lxixsxa.com/`
  - `www.lxixsxa.com/info`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/lxixsxa/info",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "information.tsx",
  "maintainers": [
    "Kiotlin"
  ],
  "module": "() => import('@/routes/lxixsxa/information.tsx')",
  "name": "News",
  "parameters": {},
  "path": "/info",
  "radar": [
    {
      "source": [
        "www.lxixsxa.com/",
        "www.lxixsxa.com/info"
      ]
    }
  ],
  "url": "www.lxixsxa.com/"
}
```
