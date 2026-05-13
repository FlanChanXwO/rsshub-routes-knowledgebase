# 浙江大学 - 物理学院

## Coverage
`index-only`

## Route
- Namespace: `zju`
- Namespace Name: `浙江大学`
- Route Path: `/physics/:type`
- Route Name: `物理学院`
- Example: `/zju/physics/1`
- URL: `physics.zju.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Caicailiushui`
- Source Location: `physics/index.ts`
- Source Module: `() => import('@/routes/zju/physics/index.ts')`

## Description
| 本院动态 | 科研进展 | 研究生教育最新消息 |
| -------- | -------- | ------------------ |
| 1        | 2        | 3                  |

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
  "description": "| 本院动态 | 科研进展 | 研究生教育最新消息 |\n| -------- | -------- | ------------------ |\n| 1        | 2        | 3                  |",
  "example": "/zju/physics/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "physics/index.ts",
  "maintainers": [
    "Caicailiushui"
  ],
  "module": "() => import('@/routes/zju/physics/index.ts')",
  "name": "物理学院",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/physics/:type"
}
```
