# Nintendo - Switch System Update（Japan）

## Coverage
`index-only`

## Route
- Namespace: `nintendo`
- Namespace Name: `Nintendo`
- Route Path: `/system-update`
- Route Name: `Switch System Update（Japan）`
- Example: `/nintendo/system-update`
- URL: `nintendo.co.jp/support/switch/system_update/index.html`
- Language: `en`
- Categories: `game`
- Maintainers: `hoilc`
- Source Location: `system-update.ts`
- Source Module: `() => import('@/routes/nintendo/system-update.ts')`

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
  - `nintendo.co.jp/support/switch/system_update/index.html`
  - `nintendo.co.jp/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/nintendo/system-update",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "system-update.ts",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/nintendo/system-update.ts')",
  "name": "Switch System Update（Japan）",
  "parameters": {},
  "path": "/system-update",
  "radar": [
    {
      "source": [
        "nintendo.co.jp/support/switch/system_update/index.html",
        "nintendo.co.jp/"
      ]
    }
  ],
  "url": "nintendo.co.jp/support/switch/system_update/index.html"
}
```
