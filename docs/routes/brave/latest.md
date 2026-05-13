# Brave - Release Notes

## Coverage
`index-only`

## Route
- Namespace: `brave`
- Namespace Name: `Brave`
- Route Path: `/latest`
- Route Name: `Release Notes`
- Example: `/brave/latest`
- URL: `brave.com/latest`
- Language: `en`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `latest.ts`
- Source Module: `() => import('@/routes/brave/latest.ts')`

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
  - `brave.com/latest`
  - `brave.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/brave/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "latest.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/brave/latest.ts')",
  "name": "Release Notes",
  "parameters": {},
  "path": "/latest",
  "radar": [
    {
      "source": [
        "brave.com/latest",
        "brave.com/"
      ]
    }
  ],
  "url": "brave.com/latest"
}
```
