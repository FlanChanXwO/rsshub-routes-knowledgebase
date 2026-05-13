# 第一财经 - 头条

## Coverage
`index-only`

## Route
- Namespace: `yicai`
- Namespace Name: `第一财经`
- Route Path: `/headline`
- Route Name: `头条`
- Example: `/yicai/headline`
- URL: `yicai.com/`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `headline.ts`
- Source Module: `() => import('@/routes/yicai/headline.ts')`

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
  "example": "/yicai/headline",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "headline.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/yicai/headline.ts')",
  "name": "头条",
  "parameters": {},
  "path": "/headline",
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
