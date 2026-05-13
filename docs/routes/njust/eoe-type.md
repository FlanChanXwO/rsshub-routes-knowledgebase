# 南京理工大学 - 电光学院

## Coverage
`index-only`

## Route
- Namespace: `njust`
- Namespace Name: `南京理工大学`
- Route Path: `/eoe/:type?`
- Route Name: `电光学院`
- Example: `/njust/eoe/tzgg`
- URL: `jwc.njust.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `jasongzy`
- Source Location: `eoe.ts`
- Source Module: `() => import('@/routes/njust/eoe.ts')`

## Description
| 通知公告 | 新闻动态 |
| -------- | -------- |
| tzgg     | xwdt     |

## Parameters
- `type`: 分类名，见下表，默认为通知公告


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
  "description": "| 通知公告 | 新闻动态 |\n| -------- | -------- |\n| tzgg     | xwdt     |",
  "example": "/njust/eoe/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "eoe.ts",
  "maintainers": [
    "jasongzy"
  ],
  "module": "() => import('@/routes/njust/eoe.ts')",
  "name": "电光学院",
  "parameters": {
    "type": "分类名，见下表，默认为通知公告"
  },
  "path": "/eoe/:type?"
}
```
