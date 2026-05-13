# 創新拿鐵 - 分类

## Coverage
`index-only`

## Route
- Namespace: `startuplatte`
- Namespace Name: `創新拿鐵`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/startuplatte`
- URL: `startuplatte.com`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/startuplatte/index.ts')`

## Description
| 首頁 | 大師智慧 | 深度分析 | 新知介紹 |
| ---- | -------- | -------- | -------- |
|      | quote    | analysis | trend    |

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
  - `startuplatte.com/category/:category`
  - `startuplatte.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 首頁 | 大師智慧 | 深度分析 | 新知介紹 |\n| ---- | -------- | -------- | -------- |\n|      | quote    | analysis | trend    |",
  "example": "/startuplatte",
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
  "module": "() => import('@/routes/startuplatte/index.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为首頁"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "startuplatte.com/category/:category",
        "startuplatte.com/"
      ]
    }
  ]
}
```
