# 南京理工大学 - 计算机学院

## Coverage
`index-only`

## Route
- Namespace: `njust`
- Namespace Name: `南京理工大学`
- Route Path: `/cs/:type?`
- Route Name: `计算机学院`
- Example: `/njust/cs/xyxw`
- URL: `jwc.njust.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Horacecxk, jasongzy`
- Source Location: `cs.ts`
- Source Module: `() => import('@/routes/njust/cs.ts')`

## Description
| 学院新闻 | 通知公告 | 学术动态 |
| -------- | -------- | -------- |
| xyxw     | tzgg     | xsdt     |

## Parameters
- `type`: 分类名，见下表，默认为学院新闻


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
  "description": "| 学院新闻 | 通知公告 | 学术动态 |\n| -------- | -------- | -------- |\n| xyxw     | tzgg     | xsdt     |",
  "example": "/njust/cs/xyxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cs.ts",
  "maintainers": [
    "Horacecxk",
    "jasongzy"
  ],
  "module": "() => import('@/routes/njust/cs.ts')",
  "name": "计算机学院",
  "parameters": {
    "type": "分类名，见下表，默认为学院新闻"
  },
  "path": "/cs/:type?"
}
```
