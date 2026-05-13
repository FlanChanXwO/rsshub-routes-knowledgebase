# Android - Security Bulletins

## Coverage
`index-only`

## Route
- Namespace: `android`
- Namespace Name: `Android`
- Route Path: `/security-bulletin`
- Route Name: `Security Bulletins`
- Example: `/android/security-bulletin`
- URL: `source.android.com/docs/security/bulletin/asb-overview`
- Language: `en`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `security-bulletin.ts`
- Source Module: `() => import('@/routes/android/security-bulletin.ts')`

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
  - `source.android.com/docs/security/bulletin`
  - `source.android.com/docs/security/bulletin/asb-overview`
  - `source.android.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/android/security-bulletin",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "security-bulletin.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/android/security-bulletin.ts')",
  "name": "Security Bulletins",
  "parameters": {},
  "path": "/security-bulletin",
  "radar": [
    {
      "source": [
        "source.android.com/docs/security/bulletin",
        "source.android.com/docs/security/bulletin/asb-overview",
        "source.android.com/"
      ]
    }
  ],
  "url": "source.android.com/docs/security/bulletin/asb-overview"
}
```
