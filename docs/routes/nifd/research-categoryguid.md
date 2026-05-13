# 国家金融与发展实验室 - 研究

## Coverage
`index-only`

## Route
- Namespace: `nifd`
- Namespace Name: `国家金融与发展实验室`
- Route Path: `/research/:categoryGuid?`
- Route Name: `研究`
- Example: `/nifd/research/3333d2af-91d6-429b-be83-28b92f31b6d7`
- URL: `www.nifd.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `Fatpandac`
- Source Location: `research.ts`
- Source Module: `() => import('@/routes/nifd/research.ts')`

## Description
资讯类型可以从网址中获取，如：

  `http://www.nifd.cn/Research?categoryGuid=7a6a826d-b525-42aa-b550-4236e524227f` 对应 `/nifd/research/7a6a826d-b525-42aa-b550-4236e524227f`

## Parameters
- `categoryGuid`: 资讯类型，默认为周报


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
  "description": "资讯类型可以从网址中获取，如：\n\n  `http://www.nifd.cn/Research?categoryGuid=7a6a826d-b525-42aa-b550-4236e524227f` 对应 `/nifd/research/7a6a826d-b525-42aa-b550-4236e524227f`",
  "example": "/nifd/research/3333d2af-91d6-429b-be83-28b92f31b6d7",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "research.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/nifd/research.ts')",
  "name": "研究",
  "parameters": {
    "categoryGuid": "资讯类型，默认为周报"
  },
  "path": "/research/:categoryGuid?"
}
```
