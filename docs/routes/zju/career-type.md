# 浙江大学 - 就业服务平台

## Coverage
`index-only`

## Route
- Namespace: `zju`
- Namespace Name: `浙江大学`
- Route Path: `/career/:type`
- Route Name: `就业服务平台`
- Example: `/zju/career/1`
- URL: `physics.zju.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Caicailiushui`
- Source Location: `career/index.ts`
- Source Module: `() => import('@/routes/zju/career/index.ts')`

## Description
| 新闻动态 | 活动通知 | 学院通知 | 告示通知 |
| -------- | -------- | -------- | -------- |
| 1        | 2        | 3        | 4        |

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
  "description": "| 新闻动态 | 活动通知 | 学院通知 | 告示通知 |\n| -------- | -------- | -------- | -------- |\n| 1        | 2        | 3        | 4        |",
  "example": "/zju/career/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "career/index.ts",
  "maintainers": [
    "Caicailiushui"
  ],
  "module": "() => import('@/routes/zju/career/index.ts')",
  "name": "就业服务平台",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/career/:type"
}
```
