# 浙江大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `zju`
- Namespace Name: `浙江大学`
- Route Path: `/grs/:type`
- Route Name: `研究生院`
- Example: `/zju/grs/1`
- URL: `physics.zju.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Caicailiushui`
- Source Location: `grs/index.ts`
- Source Module: `() => import('@/routes/zju/grs/index.ts')`

## Description
| 全部公告 | 教学管理 | 各类资助 | 学科建设 | 海外交流 |
| -------- | -------- | -------- | -------- | -------- |
| 1        | 2        | 3        | 4        | 5        |

## Parameters
- `type`: 分类，见下表


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
    "university"
  ],
  "description": "| 全部公告 | 教学管理 | 各类资助 | 学科建设 | 海外交流 |\n| -------- | -------- | -------- | -------- | -------- |\n| 1        | 2        | 3        | 4        | 5        |",
  "example": "/zju/grs/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "grs/index.ts",
  "maintainers": [
    "Caicailiushui"
  ],
  "module": "() => import('@/routes/zju/grs/index.ts')",
  "name": "研究生院",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/grs/:type"
}
```
