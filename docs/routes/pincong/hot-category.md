# 品葱 - 精选

## Coverage
`index-only`

## Route
- Namespace: `pincong`
- Namespace Name: `品葱`
- Route Path: `/hot/:category?`
- Route Name: `精选`
- Example: `/pincong/hot`
- URL: `pincong.rocks`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `zphw`
- Source Location: `hot.ts`
- Source Module: `() => import('@/routes/pincong/hot.ts')`

## Description
_None_

## Parameters
- `category`: 分类，与官网分类 URL `category-` 后的数字对应，默认为全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/pincong/hot",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hot.ts",
  "maintainers": [
    "zphw"
  ],
  "module": "() => import('@/routes/pincong/hot.ts')",
  "name": "精选",
  "parameters": {
    "category": "分类，与官网分类 URL `category-` 后的数字对应，默认为全部"
  },
  "path": "/hot/:category?"
}
```
