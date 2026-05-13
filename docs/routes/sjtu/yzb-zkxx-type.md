# 上海交通大学 - 研究生招生网招考信息

## Coverage
`index-only`

## Route
- Namespace: `sjtu`
- Namespace Name: `上海交通大学`
- Route Path: `/yzb/zkxx/:type`
- Route Name: `研究生招生网招考信息`
- Example: `/sjtu/yzb/zkxx/sszs`
- URL: `www.sjtu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `stdrc`
- Source Location: `yzb/zkxx.ts`
- Source Module: `() => import('@/routes/sjtu/yzb/zkxx.ts')`

## Description
| 博士招生 | 硕士招生 | 港澳台招生 | 考点信息 | 院系动态 |
| -------- | -------- | ---------- | -------- | -------- |
| bszs     | sszs     | gatzs      | kdxx     | yxdt     |

## Parameters
- `type`: 无默认选项


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
  "description": "| 博士招生 | 硕士招生 | 港澳台招生 | 考点信息 | 院系动态 |\n| -------- | -------- | ---------- | -------- | -------- |\n| bszs     | sszs     | gatzs      | kdxx     | yxdt     |",
  "example": "/sjtu/yzb/zkxx/sszs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yzb/zkxx.ts",
  "maintainers": [
    "stdrc"
  ],
  "module": "() => import('@/routes/sjtu/yzb/zkxx.ts')",
  "name": "研究生招生网招考信息",
  "parameters": {
    "type": "无默认选项"
  },
  "path": "/yzb/zkxx/:type"
}
```
