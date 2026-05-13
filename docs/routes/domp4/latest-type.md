# DoMP4 影视 - 最近更新

## Coverage
`index-only`

## Route
- Namespace: `domp4`
- Namespace Name: `DoMP4 影视`
- Route Path: `/latest/:type?`
- Route Name: `最近更新`
- Example: `/domp4/latest/vod`
- URL: `www.xlmp4.com/`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `savokiss, pseudoyu`
- Source Location: `latest.ts`
- Source Module: `() => import('@/routes/domp4/latest.ts')`

## Description
_None_

## Parameters
- `type`: `vod` 代表电影，`tv` 代表电视剧，默认 vod


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
  - `www.xlmp4.com/`
  - `www.xlmp4.com/custom/update.html`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/domp4/latest/vod",
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
    "savokiss",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/domp4/latest.ts')",
  "name": "最近更新",
  "parameters": {
    "type": "`vod` 代表电影，`tv` 代表电视剧，默认 vod"
  },
  "path": "/latest/:type?",
  "radar": [
    {
      "source": [
        "www.xlmp4.com/",
        "www.xlmp4.com/custom/update.html"
      ]
    }
  ],
  "url": "www.xlmp4.com/"
}
```
