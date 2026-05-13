# JAVLibrary - Best Reviews

## Coverage
`index-only`

## Route
- Namespace: `javlibrary`
- Namespace Name: `JAVLibrary`
- Route Path: `/bestreviews/:language?/:mode?`
- Route Name: `Best Reviews`
- Example: `/javlibrary/bestreviews/en`
- URL: `javlibrary.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `bestreviews.ts`
- Source Module: `() => import('@/routes/javlibrary/bestreviews.ts')`

## Description
| Last Month | All Time |
| ---------- | -------- |
| 1          | 2        |

## Parameters
- `language`: Language, see below, Japanese by default, as `ja`
- `mode`: Mode, see below, Last Month by default, as `1`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| Last Month | All Time |\n| ---------- | -------- |\n| 1          | 2        |",
  "example": "/javlibrary/bestreviews/en",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bestreviews.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/javlibrary/bestreviews.ts')",
  "name": "Best Reviews",
  "parameters": {
    "language": "Language, see below, Japanese by default, as `ja`",
    "mode": "Mode, see below, Last Month by default, as `1`"
  },
  "path": "/bestreviews/:language?/:mode?"
}
```
