# Furstar - 画师列表

## Coverage
`index-only`

## Route
- Namespace: `furstar`
- Namespace Name: `Furstar`
- Route Path: `/artists/:lang?`
- Route Name: `画师列表`
- Example: `/furstar/artists/cn`
- URL: `furstar.jp/`
- Language: `ja`
- Categories: `shopping`
- Maintainers: `NeverBehave`
- Source Location: `artists.ts`
- Source Module: `() => import('@/routes/furstar/artists.ts')`

## Description
_None_

## Parameters
- `lang`: 语言, 留空为jp, 支持cn, en


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
  - `furstar.jp/`
- `target`: `/artists`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/furstar/artists/cn",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "artists.ts",
  "maintainers": [
    "NeverBehave"
  ],
  "module": "() => import('@/routes/furstar/artists.ts')",
  "name": "画师列表",
  "parameters": {
    "lang": "语言, 留空为jp, 支持cn, en"
  },
  "path": "/artists/:lang?",
  "radar": [
    {
      "source": [
        "furstar.jp/"
      ],
      "target": "/artists"
    }
  ],
  "url": "furstar.jp/"
}
```
