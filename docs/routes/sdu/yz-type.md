# 山东大学 - 研究生招生信息网

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/yz/:type?`
- Route Name: `研究生招生信息网`
- Example: `/sdu/yz/tzgg`
- URL: `www.sdu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `niuyi1017`
- Source Location: `yz.ts`
- Source Module: `() => import('@/routes/sdu/yz.ts')`

## Description
| 通知公告 | 招生拓展 | 政策文件 | 
| -------- | -------- |-------- |
| tzgg     | zstz     | zcwj    |

## Parameters
- `type`: 默认为`tzgg`


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
  "description": "| 通知公告 | 招生拓展 | 政策文件 | \n| -------- | -------- |-------- |\n| tzgg     | zstz     | zcwj    | ",
  "example": "/sdu/yz/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yz.ts",
  "maintainers": [
    "niuyi1017"
  ],
  "module": "() => import('@/routes/sdu/yz.ts')",
  "name": "研究生招生信息网",
  "parameters": {
    "type": "默认为`tzgg`"
  },
  "path": "/yz/:type?"
}
```
