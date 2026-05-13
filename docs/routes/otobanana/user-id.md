# OTOBANANA - Timeline タイムライン

## Coverage
`index-only`

## Route
- Namespace: `otobanana`
- Namespace Name: `OTOBANANA`
- Route Path: `/user/:id`
- Route Name: `Timeline タイムライン`
- Example: `/otobanana/user/cee16401-96b1-420f-8188-abd4d33093f1`
- URL: `otobanana.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `timeline.ts`
- Source Module: `() => import('@/routes/otobanana/timeline.ts')`

## Description
_None_

## Parameters
- `id`: User ID, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `otobanana.com/user/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/otobanana/user/cee16401-96b1-420f-8188-abd4d33093f1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "timeline.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/otobanana/timeline.ts')",
  "name": "Timeline タイムライン",
  "parameters": {
    "id": "User ID, can be found in URL"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "otobanana.com/user/:id"
      ]
    }
  ]
}
```
