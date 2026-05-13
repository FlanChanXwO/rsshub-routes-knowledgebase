# 中国人工智能学会 - 学会动态

## Coverage
`index-only`

## Route
- Namespace: `caai`
- Namespace Name: `中国人工智能学会`
- Route Path: `/:caty`
- Route Name: `学会动态`
- Example: `/caai/45`
- URL: `caai.cn`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `tudou027`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/caai/index.ts')`

## Description
_None_

## Parameters
- `caty`: 分类 ID，可在 URL 找到


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
    "study"
  ],
  "example": "/caai/45",
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
    "tudou027"
  ],
  "module": "() => import('@/routes/caai/index.ts')",
  "name": "学会动态",
  "parameters": {
    "caty": "分类 ID，可在 URL 找到"
  },
  "path": "/:caty"
}
```
