# Unraid - Community Apps

## Coverage
`index-only`

## Route
- Namespace: `unraid`
- Namespace Name: `Unraid`
- Route Path: `/community-apps`
- Route Name: `Community Apps`
- Example: `/unraid/community-apps`
- URL: `unraid.net/community/apps`
- Language: `en`
- Categories: `program-update`
- Maintainers: `KTachibanaM`
- Source Location: `community-apps.ts`
- Source Module: `() => import('@/routes/unraid/community-apps.ts')`

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
  - `unraid.net/community/apps`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/unraid/community-apps",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "community-apps.ts",
  "maintainers": [
    "KTachibanaM"
  ],
  "module": "() => import('@/routes/unraid/community-apps.ts')",
  "name": "Community Apps",
  "parameters": {},
  "path": "/community-apps",
  "radar": [
    {
      "source": [
        "unraid.net/community/apps"
      ]
    }
  ],
  "url": "unraid.net/community/apps"
}
```
