# 早报网 - 每日早报

## Coverage
`index-only`

## Route
- Namespace: `qqorw`
- Namespace Name: `早报网`
- Route Path: `/:category?`
- Route Name: `每日早报`
- Example: `/qqorw`
- URL: `qqorw.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/qqorw/index.ts')`

## Description
| 首页 | 每日早报 | 国际早报 | 生活冷知识 |
| ---- | -------- | -------- | ---------- |
|      | mrzb     | zbapp    | zbzzd      |

## Parameters
- `category`: 分类，见下表，默认为首页


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
  - `qqorw.cn/:category`
  - `qqorw.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 首页 | 每日早报 | 国际早报 | 生活冷知识 |\n| ---- | -------- | -------- | ---------- |\n|      | mrzb     | zbapp    | zbzzd      |",
  "example": "/qqorw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/qqorw/index.ts')",
  "name": "每日早报",
  "parameters": {
    "category": "分类，见下表，默认为首页"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "qqorw.cn/:category",
        "qqorw.cn/"
      ]
    }
  ]
}
```
