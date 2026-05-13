# MySQL - Release Notes

## Coverage
`index-only`

## Route
- Namespace: `mysql`
- Namespace Name: `MySQL`
- Route Path: `/release/:version?`
- Route Name: `Release Notes`
- Example: `/mysql/release/8.0`
- URL: `dev.mysql.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `release.ts`
- Source Module: `() => import('@/routes/mysql/release.ts')`

## Description
| 8.0 | 5.7 | 5.6 |
| --- | --- | --- |

## Parameters
- `version`: Version, see below, 8.0 by default


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
    "programming"
  ],
  "description": "| 8.0 | 5.7 | 5.6 |\n| --- | --- | --- |",
  "example": "/mysql/release/8.0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "release.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/mysql/release.ts')",
  "name": "Release Notes",
  "parameters": {
    "version": "Version, see below, 8.0 by default"
  },
  "path": "/release/:version?"
}
```
