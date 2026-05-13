# Chocolatey - Package

## Coverage
`index-only`

## Route
- Namespace: `chocolatey`
- Namespace Name: `Chocolatey`
- Route Path: `/packages/:id`
- Route Name: `Package`
- Example: `/chocolatey/packages/microsoft-edge`
- URL: `community.chocolatey.org`
- Language: `en`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `packages.ts`
- Source Module: `() => import('@/routes/chocolatey/packages.ts')`

## Description
_None_

## Parameters
- `id`: {"description": "Package ID"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `community.chocolatey.org/packages`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/chocolatey/packages/microsoft-edge",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "packages.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/chocolatey/packages.ts')",
  "name": "Package",
  "parameters": {
    "id": {
      "description": "Package ID"
    }
  },
  "path": "/packages/:id",
  "radar": [
    {
      "source": [
        "community.chocolatey.org/packages"
      ]
    }
  ],
  "url": "community.chocolatey.org",
  "view": 5,
  "zh": {
    "example": "/chocolatey/package/microsoft-edge",
    "maintainers": [
      "nczitzk"
    ],
    "name": "程序包",
    "parameters": {
      "id": {
        "description": "程序包 ID"
      }
    },
    "path": "/packages/:id",
    "url": "community.chocolatey.org"
  }
}
```
