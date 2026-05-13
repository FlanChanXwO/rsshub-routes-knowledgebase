# 安全内参 - 分类

## Coverage
`index-only`

## Route
- Namespace: `secrss`
- Namespace Name: `安全内参`
- Route Path: `/category/:category?`
- Route Name: `分类`
- Example: `/secrss/category/产业趋势`
- URL: `secrss.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `XinRoom, SunBK201`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/secrss/category.ts')`

## Description
_None_

## Parameters
- `category`: N


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
    "programming"
  ],
  "example": "/secrss/category/产业趋势",
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
    "XinRoom",
    "SunBK201"
  ],
  "module": "() => import('@/routes/secrss/category.ts')",
  "name": "分类",
  "parameters": {
    "category": "N"
  },
  "path": "/category/:category?"
}
```
