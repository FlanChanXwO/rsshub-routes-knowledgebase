# 加美财经 - 分类

## Coverage
`index-only`

## Route
- Namespace: `caus`
- Namespace Name: `加美财经`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/caus`
- URL: `caus.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/caus/index.ts')`

## Description
| 全部 | 要闻 | 商业 | 快讯 | 财富 | 生活 |
| ---- | ---- | ---- | ---- | ---- | ---- |
| 0    | 1    | 2    | 3    | 8    | 6    |

## Parameters
- `category`: 分类，见下表，默认为全部


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
  "description": "| 全部 | 要闻 | 商业 | 快讯 | 财富 | 生活 |\n| ---- | ---- | ---- | ---- | ---- | ---- |\n| 0    | 1    | 2    | 3    | 8    | 6    |",
  "example": "/caus",
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
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/caus/index.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/:category?"
}
```
