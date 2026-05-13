# コラボカフェ - 分类

## Coverage
`index-only`

## Route
- Namespace: `collabo-cafe`
- Namespace Name: `コラボカフェ`
- Route Path: `/category/:category`
- Route Name: `分类`
- Example: `/collabo-cafe/category/cafe`
- URL: `collabo-cafe.com`
- Language: `ja`
- Categories: `anime`
- Maintainers: `cokemine`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/collabo-cafe/category.ts')`

## Description
_None_

## Parameters
- `category`: Category, refer to the original website (ジャンル別)


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
    "anime"
  ],
  "example": "/collabo-cafe/category/cafe",
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
    "cokemine"
  ],
  "module": "() => import('@/routes/collabo-cafe/category.ts')",
  "name": "分类",
  "parameters": {
    "category": "Category, refer to the original website (ジャンル別)"
  },
  "path": "/category/:category"
}
```
