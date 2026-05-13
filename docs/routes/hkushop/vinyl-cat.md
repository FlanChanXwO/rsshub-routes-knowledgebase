# 環球唱片(香港)官方網上商店 - HKU Shop 黑胶专区

## Coverage
`index-only`

## Route
- Namespace: `hkushop`
- Namespace Name: `環球唱片(香港)官方網上商店`
- Route Path: `/vinyl/:cat?`
- Route Name: `HKU Shop 黑胶专区`
- Example: `/hkushop/vinyl`
- URL: `hkushop.com/vinyl-or-picture-lp.html`
- Language: `zh-HK`
- Categories: `shopping`
- Maintainers: `gideonsenku`
- Source Location: `vinyl-or-picture-lp.ts`
- Source Module: `() => import('@/routes/hkushop/vinyl-or-picture-lp.ts')`

## Description
常见分类:
| 華語音樂 | 經典復刻 | 古典跨界 | 爵士音樂 | 國際音樂 | 電影原聲帶 | 黑膠日本音樂 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 37 | 38 | 40 | 41 | 39 | 170 | 224 |

## Parameters
- `cat`: 分类，见下表，默认不分类


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `hkushop.com/vinyl-or-picture-lp.html`
  - `hkushop.com/`
- `target`: `/vinyl`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "常见分类:\n| 華語音樂 | 經典復刻 | 古典跨界 | 爵士音樂 | 國際音樂 | 電影原聲帶 | 黑膠日本音樂 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| 37 | 38 | 40 | 41 | 39 | 170 | 224 |",
  "example": "/hkushop/vinyl",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "vinyl-or-picture-lp.ts",
  "maintainers": [
    "gideonsenku"
  ],
  "module": "() => import('@/routes/hkushop/vinyl-or-picture-lp.ts')",
  "name": "HKU Shop 黑胶专区",
  "parameters": {
    "cat": "分类，见下表，默认不分类"
  },
  "path": "/vinyl/:cat?",
  "radar": [
    {
      "source": [
        "hkushop.com/vinyl-or-picture-lp.html",
        "hkushop.com/"
      ],
      "target": "/vinyl"
    }
  ],
  "url": "hkushop.com/vinyl-or-picture-lp.html"
}
```
