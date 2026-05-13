# Readhub - 分类

## Coverage
`index-only`

## Route
- Namespace: `readhub`
- Namespace Name: `Readhub`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/readhub`
- URL: `readhub.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `WhiteWorld, nczitzk, Fatpandac`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/readhub/index.ts')`

## Description
| 热门话题 | 科技动态 | 医疗产业 | 财经快讯           |
| -------- | -------- | -------- | ------------------ |
|          | news     | medical  | financial_express |

## Parameters
- `category`: 分类，见下表，默认为热门话题


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 热门话题 | 科技动态 | 医疗产业 | 财经快讯           |\n| -------- | -------- | -------- | ------------------ |\n|          | news     | medical  | financial_express |",
  "example": "/readhub",
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
    "WhiteWorld",
    "nczitzk",
    "Fatpandac"
  ],
  "module": "() => import('@/routes/readhub/index.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为热门话题"
  },
  "path": "/:category?"
}
```
