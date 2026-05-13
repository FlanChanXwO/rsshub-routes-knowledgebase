# 南京大学 - 科学技术处

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/scit/:type`
- Route Name: `科学技术处`
- Example: `/nju/scit/tzgg`
- URL: `admission.nju.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `scit.ts`
- Source Module: `() => import('@/routes/nju/scit.ts')`

## Description
| 通知公告 | 科研动态 |
| -------- | -------- |
| tzgg     | kydt     |

## Parameters
- `type`: 分类名


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
  "description": "| 通知公告 | 科研动态 |\n| -------- | -------- |\n| tzgg     | kydt     |",
  "example": "/nju/scit/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "scit.ts",
  "maintainers": [
    "ret-1"
  ],
  "module": "() => import('@/routes/nju/scit.ts')",
  "name": "科学技术处",
  "parameters": {
    "type": "分类名"
  },
  "path": "/scit/:type"
}
```
