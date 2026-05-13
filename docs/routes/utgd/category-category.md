# UNTAG - 分类

## Coverage
`index-only`

## Route
- Namespace: `utgd`
- Namespace Name: `UNTAG`
- Route Path: `/category/:category?`
- Route Name: `分类`
- Example: `/utgd/category/method`
- URL: `utgd.net`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/utgd/category.ts')`

## Description
| 方法   | 观点    |
| ------ | ------- |
| method | opinion |

## Parameters
- `category`: 分类，可在对应分类页的 URL 中找到，默认为方法


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
  - `utgd.net/category/s/:category`
  - `utgd.net/`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 方法   | 观点    |\n| ------ | ------- |\n| method | opinion |",
  "example": "/utgd/category/method",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/utgd/category.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类，可在对应分类页的 URL 中找到，默认为方法"
  },
  "path": "/category/:category?",
  "radar": [
    {
      "source": [
        "utgd.net/category/s/:category",
        "utgd.net/"
      ],
      "target": "/category/:category"
    }
  ]
}
```
