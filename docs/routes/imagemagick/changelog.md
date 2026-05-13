# ImageMagick - Changelog

## Coverage
`index-only`

## Route
- Namespace: `imagemagick`
- Namespace Name: `ImageMagick`
- Route Path: `/changelog`
- Route Name: `Changelog`
- Example: `/imagemagick/changelog`
- URL: `imagemagick.org/script/download.php`
- Language: `en`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `changelog.ts`
- Source Module: `() => import('@/routes/imagemagick/changelog.ts')`

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
  - `imagemagick.org/script/download.php`
  - `imagemagick.org/script`
  - `imagemagick.org/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/imagemagick/changelog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "changelog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/imagemagick/changelog.ts')",
  "name": "Changelog",
  "parameters": {},
  "path": "/changelog",
  "radar": [
    {
      "source": [
        "imagemagick.org/script/download.php",
        "imagemagick.org/script",
        "imagemagick.org/"
      ]
    }
  ],
  "url": "imagemagick.org/script/download.php"
}
```
