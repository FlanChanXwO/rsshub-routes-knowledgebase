# 報導者 - 最新

## Coverage
`index-only`

## Route
- Namespace: `twreporter`
- Namespace Name: `報導者`
- Route Path: `/newest`
- Route Name: `最新`
- Example: `/twreporter/newest`
- URL: `twreporter.org/`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `newest.ts`
- Source Module: `() => import('@/routes/twreporter/newest.ts')`

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
  - `twreporter.org/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/twreporter/newest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "newest.ts",
  "maintainers": [
    "emdoe"
  ],
  "module": "() => import('@/routes/twreporter/newest.ts')",
  "name": "最新",
  "parameters": {},
  "path": "/newest",
  "radar": [
    {
      "source": [
        "twreporter.org/"
      ]
    }
  ],
  "url": "twreporter.org/"
}
```
