# 信报财经新闻 - 即时新闻

## Coverage
`index-only`

## Route
- Namespace: `hkej`
- Namespace Name: `信报财经新闻`
- Route Path: `/:category?`
- Route Name: `即时新闻`
- Example: `/hkej/index`
- URL: `hkej.com/`
- Language: `zh-HK`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/hkej/index.tsx')`

## Description
| index    | stock    | hongkong | china    | international | property | current  |
| -------- | -------- | -------- | -------- | ------------- | -------- | -------- |
| 全部新闻 | 港股直击 | 香港财经 | 中国财经 | 国际财经      | 地产新闻 | 时事脉搏 |

## Parameters
- `category`: 分类，默认为全部新闻


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `hkej.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| index    | stock    | hongkong | china    | international | property | current  |\n| -------- | -------- | -------- | -------- | ------------- | -------- | -------- |\n| 全部新闻 | 港股直击 | 香港财经 | 中国财经 | 国际财经      | 地产新闻 | 时事脉搏 |",
  "example": "/hkej/index",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/hkej/index.tsx')",
  "name": "即时新闻",
  "parameters": {
    "category": "分类，默认为全部新闻"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "hkej.com/"
      ]
    }
  ],
  "url": "hkej.com/"
}
```
