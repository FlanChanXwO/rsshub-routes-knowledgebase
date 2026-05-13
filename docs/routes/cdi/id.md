# 国家高端智库 / 综合开发研究院 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `cdi`
- Namespace Name: `国家高端智库 / 综合开发研究院`
- Route Path: `/:id?`
- Route Name: `栏目`
- Example: `/cdi`
- URL: `cdi.com.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/cdi/index.ts')`

## Description
| 樊纲观点 | 综研国策 | 综研观察 | 综研专访 | 综研视点 | 银湖新能源 |
| -------- | -------- | -------- | -------- | -------- | ---------- |
| 102      | 152      | 150      | 153      | 154      | 151        |

## Parameters
- `id`: 分类，见下表，默认为综研国策


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
  "description": "| 樊纲观点 | 综研国策 | 综研观察 | 综研专访 | 综研视点 | 银湖新能源 |\n| -------- | -------- | -------- | -------- | -------- | ---------- |\n| 102      | 152      | 150      | 153      | 154      | 151        |",
  "example": "/cdi",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/cdi/index.ts')",
  "name": "栏目",
  "parameters": {
    "id": "分类，见下表，默认为综研国策"
  },
  "path": "/:id?"
}
```
