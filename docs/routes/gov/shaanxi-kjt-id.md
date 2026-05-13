# 国家能源局 - 省科学技术厅

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/shaanxi/kjt/:id?`
- Route Name: `省科学技术厅`
- Example: `/gov/shaanxi/kjt`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `shaanxi/kjt.ts`
- Source Module: `() => import('@/routes/gov/shaanxi/kjt.ts')`

## Description
| 科技头条 | 工作动态 | 基层科技 | 科技博览 | 媒体聚焦 | 通知公告 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| 1061     | 24       | 27       | 25       | 28       | 221      |

## Parameters
- `id`: 分类，见下表，默认为通知公告


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
    "government"
  ],
  "description": "| 科技头条 | 工作动态 | 基层科技 | 科技博览 | 媒体聚焦 | 通知公告 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| 1061     | 24       | 27       | 25       | 28       | 221      |",
  "example": "/gov/shaanxi/kjt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "shaanxi/kjt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gov/shaanxi/kjt.ts')",
  "name": "省科学技术厅",
  "parameters": {
    "id": "分类，见下表，默认为通知公告"
  },
  "path": "/shaanxi/kjt/:id?"
}
```
