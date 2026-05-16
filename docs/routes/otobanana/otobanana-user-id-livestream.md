# OTOBANANA - Livestream ライブ配信

## Coverage
`index-only`

## Route
- Namespace: `otobanana`
- Namespace Name: `OTOBANANA`
- Route Path: `/otobanana/user/:id/livestream`
- Route Name: `Livestream ライブ配信`
- Example: `/otobanana/user/cee16401-96b1-420f-8188-abd4d33093f1/livestream`
- URL: `otobanana.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `livestream.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: User ID, can be found in URL


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
  - `otobanana.com/user/:id/livestream`
  - `otobanana.com/user/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/otobanana/user/cee16401-96b1-420f-8188-abd4d33093f1/livestream",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "livestream.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Livestream ライブ配信",
  "parameters": {
    "id": "User ID, can be found in URL"
  },
  "path": "/user/:id/livestream",
  "radar": [
    {
      "source": [
        "otobanana.com/user/:id/livestream",
        "otobanana.com/user/:id"
      ]
    }
  ],
  "topFeeds": []
}
```
