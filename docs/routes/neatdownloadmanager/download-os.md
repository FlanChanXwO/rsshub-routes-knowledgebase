# Neat Download Manager - Download

## Coverage
`index-only`

## Route
- Namespace: `neatdownloadmanager`
- Namespace Name: `Neat Download Manager`
- Route Path: `/download/:os?`
- Route Name: `Download`
- Example: `/neatdownloadmanager/download`
- URL: `neatdownloadmanager.com/index.php`
- Language: `en`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `download.ts`
- Source Module: `() => import('@/routes/neatdownloadmanager/download.ts')`

## Description
_None_

## Parameters
- `os`: Operating system, windows or macos, all by default


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
  - `neatdownloadmanager.com/index.php`
  - `neatdownloadmanager.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/neatdownloadmanager/download",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "download.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/neatdownloadmanager/download.ts')",
  "name": "Download",
  "parameters": {
    "os": "Operating system, windows or macos, all by default"
  },
  "path": "/download/:os?",
  "radar": [
    {
      "source": [
        "neatdownloadmanager.com/index.php",
        "neatdownloadmanager.com/"
      ]
    }
  ],
  "url": "neatdownloadmanager.com/index.php"
}
```
