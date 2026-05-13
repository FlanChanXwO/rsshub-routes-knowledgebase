# 第一财经 - VIP 频道

## Coverage
`index-only`

## Route
- Namespace: `yicai`
- Namespace Name: `第一财经`
- Route Path: `/vip/:id?`
- Route Name: `VIP 频道`
- Example: `/yicai/vip/428`
- URL: `yicai.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `vip.ts`
- Source Module: `() => import('@/routes/yicai/vip.ts')`

## Description
_None_

## Parameters
- `id`: 频道 id，可在对应频道页中找到，默认为一元点金


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
  - `yicai.com/vip/product/:id`
  - `yicai.com/`
- `target`: `/vip/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/yicai/vip/428",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "vip.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/yicai/vip.ts')",
  "name": "VIP 频道",
  "parameters": {
    "id": "频道 id，可在对应频道页中找到，默认为一元点金"
  },
  "path": "/vip/:id?",
  "radar": [
    {
      "source": [
        "yicai.com/vip/product/:id",
        "yicai.com/"
      ],
      "target": "/vip/:id"
    }
  ]
}
```
