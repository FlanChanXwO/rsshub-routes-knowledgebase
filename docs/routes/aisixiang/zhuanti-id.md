# 爱思想 - 专题

## Coverage
`index-only`

## Route
- Namespace: `aisixiang`
- Namespace Name: `爱思想`
- Route Path: `/zhuanti/:id`
- Route Name: `专题`
- Example: `/aisixiang/zhuanti/211`
- URL: `aisixiang.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `zhuanti.ts`
- Source Module: `() => import('@/routes/aisixiang/zhuanti.ts')`

## Description
::: tip
  更多专题请见 [关键词](http://www.aisixiang.com/zhuanti/)
:::

## Parameters
- `id`: 专题 ID, 可在对应专题 URL 中找到


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
    "reading"
  ],
  "description": "::: tip\n  更多专题请见 [关键词](http://www.aisixiang.com/zhuanti/)\n:::",
  "example": "/aisixiang/zhuanti/211",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "zhuanti.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/aisixiang/zhuanti.ts')",
  "name": "专题",
  "parameters": {
    "id": "专题 ID, 可在对应专题 URL 中找到"
  },
  "path": "/zhuanti/:id"
}
```
