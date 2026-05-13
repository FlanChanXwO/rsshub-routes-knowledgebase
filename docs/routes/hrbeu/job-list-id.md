# 哈尔滨工程大学 - 就业服务平台

## Coverage
`index-only`

## Route
- Namespace: `hrbeu`
- Namespace Name: `哈尔滨工程大学`
- Route Path: `/job/list/:id`
- Route Name: `就业服务平台`
- Example: `/hrbeu/job/list/tzgg`
- URL: `yjsy.hrbeu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Derekmini`
- Source Location: `job/list.ts`
- Source Module: `() => import('@/routes/hrbeu/job/list.ts')`

## Description
| 通知公告 | 热点新闻 |
| :------: | :------: |
|   tzgg   |   rdxw   |

## Parameters
- `id`: 栏目，如下表


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
  "description": "| 通知公告 | 热点新闻 |\n| :------: | :------: |\n|   tzgg   |   rdxw   |",
  "example": "/hrbeu/job/list/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "job/list.ts",
  "maintainers": [
    "Derekmini"
  ],
  "module": "() => import('@/routes/hrbeu/job/list.ts')",
  "name": "就业服务平台",
  "parameters": {
    "id": "栏目，如下表"
  },
  "path": "/job/list/:id"
}
```
