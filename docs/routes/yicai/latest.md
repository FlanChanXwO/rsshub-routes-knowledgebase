# 第一财经 - 最新

## Coverage
`index-only`

## Route
- Namespace: `yicai`
- Namespace Name: `第一财经`
- Route Path: `/latest`
- Route Name: `最新`
- Example: `/yicai/latest`
- URL: `yicai.com/`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `latest.ts`
- Source Module: `() => import('@/routes/yicai/latest.ts')`

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
  - `yicai.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/yicai/latest",
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
  "module": "() => import('@/routes/yicai/latest.ts')",
  "name": "最新",
  "parameters": {},
  "path": "/latest",
  "radar": [
    {
      "source": [
        "yicai.com/"
      ]
    }
  ],
  "url": "yicai.com/"
}
```
