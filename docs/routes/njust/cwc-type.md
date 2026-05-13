# 南京理工大学 - 财务处

## Coverage
`index-only`

## Route
- Namespace: `njust`
- Namespace Name: `南京理工大学`
- Route Path: `/cwc/:type?`
- Route Name: `财务处`
- Example: `/njust/cwc/tzgg`
- URL: `jwc.njust.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `MilkShakeYoung, jasongzy`
- Source Location: `cwc.ts`
- Source Module: `() => import('@/routes/njust/cwc.ts')`

## Description
| 通知公告 | 办事流程 |
| -------- | -------- |
| tzgg     | bslc     |

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
  "description": "| 通知公告 | 办事流程 |\n| -------- | -------- |\n| tzgg     | bslc     |",
  "example": "/njust/cwc/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cwc.ts",
  "maintainers": [
    "MilkShakeYoung",
    "jasongzy"
  ],
  "module": "() => import('@/routes/njust/cwc.ts')",
  "name": "财务处",
  "parameters": {
    "type": "分类名，见下表，默认为通知公告"
  },
  "path": "/cwc/:type?"
}
```
