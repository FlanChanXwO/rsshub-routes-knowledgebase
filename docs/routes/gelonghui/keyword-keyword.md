# 格隆汇 - 搜索关键字

## Coverage
`index-only`

## Route
- Namespace: `gelonghui`
- Namespace Name: `格隆汇`
- Route Path: `/keyword/:keyword`
- Route Name: `搜索关键字`
- Example: `/gelonghui/keyword/早报`
- URL: `gelonghui.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `keyword.ts`
- Source Module: `() => import('@/routes/gelonghui/keyword.ts')`

## Description
_None_

## Parameters
- `keyword`: 搜索关键字


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
    "finance"
  ],
  "example": "/gelonghui/keyword/早报",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "keyword.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gelonghui/keyword.ts')",
  "name": "搜索关键字",
  "parameters": {
    "keyword": "搜索关键字"
  },
  "path": "/keyword/:keyword",
  "view": 0
}
```
