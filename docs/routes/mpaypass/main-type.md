# 移动支付网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `mpaypass`
- Namespace Name: `移动支付网`
- Route Path: `/main/:type?`
- Route Name: `分类`
- Example: `/mpaypass/main/policy`
- URL: `mpaypass.com.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `zhuan-zhu`
- Source Location: `main.ts`
- Source Module: `() => import('@/routes/mpaypass/main.ts')`

## Description
_None_

## Parameters
- `type`: 新闻类型，类型可在URL中找到，类似`policy`，`eye`等，空或其他任意值展示最新新闻


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
  "example": "/mpaypass/main/policy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "main.ts",
  "maintainers": [
    "zhuan-zhu"
  ],
  "module": "() => import('@/routes/mpaypass/main.ts')",
  "name": "分类",
  "parameters": {
    "type": "新闻类型，类型可在URL中找到，类似`policy`，`eye`等，空或其他任意值展示最新新闻"
  },
  "path": "/main/:type?"
}
```
