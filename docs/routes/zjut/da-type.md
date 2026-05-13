# 浙江工业大学 - 设计与建筑学院

## Coverage
`index-only`

## Route
- Namespace: `zjut`
- Namespace Name: `浙江工业大学`
- Route Path: `/da/:type`
- Route Name: `设计与建筑学院`
- Example: `/zjut/da/1`
- URL: `www.design.zjut.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `yikZero`
- Source Location: `da/index.ts`
- Source Module: `() => import('@/routes/zjut/da/index.ts')`

## Description
| 学院新闻 | 公告通知 | 科研申报 | 科研成果 | 文件与资源 | 学术交流 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| 1        | 2        | 3        | 4        | 5        | 6        |

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
  "description": "| 学院新闻 | 公告通知 | 科研申报 | 科研成果 | 文件与资源 | 学术交流 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| 1        | 2        | 3        | 4        | 5        | 6        |",
  "example": "/zjut/da/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "da/index.ts",
  "maintainers": [
    "yikZero"
  ],
  "module": "() => import('@/routes/zjut/da/index.ts')",
  "name": "设计与建筑学院",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/da/:type",
  "url": "www.design.zjut.edu.cn"
}
```
