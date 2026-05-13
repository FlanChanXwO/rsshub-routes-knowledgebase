# 聯合新聞網 - 轉角國際 - 首頁

## Coverage
`index-only`

## Route
- Namespace: `udn`
- Namespace Name: `聯合新聞網`
- Route Path: `/global/:category?`
- Route Name: `轉角國際 - 首頁`
- Example: `/udn/global`
- URL: `udn.com`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `global/index.ts`
- Source Module: `() => import('@/routes/udn/global/index.ts')`

## Description
| 首頁 | 編輯精選 | 熱門文章 |
| ---- | -------- | -------- |
|      | editor   | hot      |

## Parameters
- `category`: 分类，见下表，默认为首頁


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
  - `global.udn.com/global_vision/index`
  - `global.udn.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 首頁 | 編輯精選 | 熱門文章 |\n| ---- | -------- | -------- |\n|      | editor   | hot      |",
  "example": "/udn/global",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "global/index.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/udn/global/index.ts')",
  "name": "轉角國際 - 首頁",
  "parameters": {
    "category": "分类，见下表，默认为首頁"
  },
  "path": "/global/:category?",
  "radar": [
    {
      "source": [
        "global.udn.com/global_vision/index",
        "global.udn.com/"
      ]
    }
  ]
}
```
