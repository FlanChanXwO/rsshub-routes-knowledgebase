# Infuse - Release Notes

## Coverage
`index-only`

## Route
- Namespace: `firecore`
- Namespace Name: `Infuse`
- Route Path: `/:os`
- Route Name: `Release Notes`
- Example: `/firecore/ios`
- URL: `firecore.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `NathanDai`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/firecore/index.ts')`

## Description
_None_

## Parameters
- `os`: `ios`,`tvos`,`macos`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/firecore/ios",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "NathanDai"
  ],
  "module": "() => import('@/routes/firecore/index.ts')",
  "name": "Release Notes",
  "parameters": {
    "os": "`ios`,`tvos`,`macos`"
  },
  "path": "/:os"
}
```
