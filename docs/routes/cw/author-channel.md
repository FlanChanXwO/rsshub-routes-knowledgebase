# 天下雜誌 - 作者

## Coverage
`index-only`

## Route
- Namespace: `cw`
- Namespace Name: `天下雜誌`
- Route Path: `/author/:channel`
- Route Name: `作者`
- Example: `/cw/author/57`
- URL: `cw.com.tw`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `author.ts`
- Source Module: `() => import('@/routes/cw/author.ts')`

## Description
_None_

## Parameters
- `channel`: 作者 ID，可在 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cw.com.tw/author/:channel`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/cw/author/57",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "author.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/cw/author.ts')",
  "name": "作者",
  "parameters": {
    "channel": "作者 ID，可在 URL 中找到"
  },
  "path": "/author/:channel",
  "radar": [
    {
      "source": [
        "cw.com.tw/author/:channel"
      ]
    }
  ]
}
```
