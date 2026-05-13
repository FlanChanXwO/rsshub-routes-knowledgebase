# 理论网 - 学习时报

## Coverage
`index-only`

## Route
- Namespace: `cntheory`
- Namespace Name: `理论网`
- Route Path: `/paper/:id?`
- Route Name: `学习时报`
- Example: `/cntheory/paper`
- URL: `paper.cntheory.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `paper.tsx`
- Source Module: `() => import('@/routes/cntheory/paper.tsx')`

## Description
如订阅 **第 A1 版：国内大局**，路由为 [`/cntheory/paper/国内大局`](https://rsshub.app/cntheory/paper/国内大局)。

## Parameters
- `id`: 板块，默认为全部


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
  "description": "如订阅 **第 A1 版：国内大局**，路由为 [`/cntheory/paper/国内大局`](https://rsshub.app/cntheory/paper/国内大局)。",
  "example": "/cntheory/paper",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "paper.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/cntheory/paper.tsx')",
  "name": "学习时报",
  "parameters": {
    "id": "板块，默认为全部"
  },
  "path": "/paper/:id?"
}
```
