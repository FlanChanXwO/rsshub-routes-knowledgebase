# 量子位 - 分类

## Coverage
`index-only`

## Route
- Namespace: `qbitai`
- Namespace Name: `量子位`
- Route Path: `/category/:category`
- Route Name: `分类`
- Example: `/qbitai/category/资讯`
- URL: `qbitai.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `FuryMartin, Geraldxm`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/qbitai/category.ts')`

## Description
| 资讯 | 数码     | 智能车 | 智库  | 活动    |
| ---- | -------- | ------ | ----- | ------- |
| 资讯 | ebandeng | auto   | zhiku | huodong |

## Parameters
- `category`: 分类名，见下表


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
  - `qbitai.com/category/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 资讯 | 数码     | 智能车 | 智库  | 活动    |\n| ---- | -------- | ------ | ----- | ------- |\n| 资讯 | ebandeng | auto   | zhiku | huodong |",
  "example": "/qbitai/category/资讯",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "category.ts",
  "maintainers": [
    "FuryMartin, Geraldxm"
  ],
  "module": "() => import('@/routes/qbitai/category.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类名，见下表"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "qbitai.com/category/:category"
      ]
    }
  ]
}
```
