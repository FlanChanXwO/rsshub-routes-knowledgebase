# 联合早报 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `zaobao`
- Namespace Name: `联合早报`
- Route Path: `/znews/:section?`
- Route Name: `新闻`
- Example: `/zaobao/znews/china`
- URL: `www.zaobao.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `shunf4`
- Source Location: `znews.ts`
- Source Module: `() => import('@/routes/zaobao/znews.ts')`

## Description
| 中国  | 新加坡    | 东南亚 | 国际  | 体育   |
| ----- | --------- | ------ | ----- | ------ |
| china | singapore | sea    | world | sports |

## Parameters
- `section`: 分类，缺省为 china


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
    "traditional-media"
  ],
  "description": "| 中国  | 新加坡    | 东南亚 | 国际  | 体育   |\n| ----- | --------- | ------ | ----- | ------ |\n| china | singapore | sea    | world | sports |",
  "example": "/zaobao/znews/china",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "znews.ts",
  "maintainers": [
    "shunf4"
  ],
  "module": "() => import('@/routes/zaobao/znews.ts')",
  "name": "新闻",
  "parameters": {
    "section": "分类，缺省为 china"
  },
  "path": "/znews/:section?"
}
```
