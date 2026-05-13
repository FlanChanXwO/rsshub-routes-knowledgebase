# Mixcloud - User

## Coverage
`index-only`

## Route
- Namespace: `mixcloud`
- Namespace Name: `Mixcloud`
- Route Path: `/:username/:type?`
- Route Name: `User`
- Example: `/mixcloud/dholbach/uploads`
- URL: `www.mixcloud.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `Misaka13514`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/mixcloud/index.ts')`

## Description
| Shows   | Reposts | Favorites | History | Stream |
| ------- | ------- | --------- | ------- | ------ |
| uploads | reposts | favorites | listens | stream |

## Parameters
- `username`: Username, can be found in URL
- `type`: Type, see below, uploads by default


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
  - `mixcloud.com/:username/:type?`
### Rule 2
- `source`:
  - `www.mixcloud.com/:username/:type?`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| Shows   | Reposts | Favorites | History | Stream |\n| ------- | ------- | --------- | ------- | ------ |\n| uploads | reposts | favorites | listens | stream |",
  "example": "/mixcloud/dholbach/uploads",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "Misaka13514"
  ],
  "module": "() => import('@/routes/mixcloud/index.ts')",
  "name": "User",
  "parameters": {
    "type": "Type, see below, uploads by default",
    "username": "Username, can be found in URL"
  },
  "path": "/:username/:type?",
  "radar": [
    {
      "source": [
        "mixcloud.com/:username/:type?"
      ]
    },
    {
      "source": [
        "www.mixcloud.com/:username/:type?"
      ]
    }
  ]
}
```
