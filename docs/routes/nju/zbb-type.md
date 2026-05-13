# 南京大学 - 招标办公室

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/zbb/:type`
- Route Name: `招标办公室`
- Example: `/nju/zbb/cgxx`
- URL: `admission.nju.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `zbb.ts`
- Source Module: `() => import('@/routes/nju/zbb.ts')`

## Description
| 采购信息 | 成交公示 | 政府采购意向公开 |
| -------- | -------- | ---------------- |
| cgxx     | cjgs     | zfcgyxgk         |

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
  "description": "| 采购信息 | 成交公示 | 政府采购意向公开 |\n| -------- | -------- | ---------------- |\n| cgxx     | cjgs     | zfcgyxgk         |",
  "example": "/nju/zbb/cgxx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "zbb.ts",
  "maintainers": [
    "ret-1"
  ],
  "module": "() => import('@/routes/nju/zbb.ts')",
  "name": "招标办公室",
  "parameters": {
    "type": "分类名"
  },
  "path": "/zbb/:type"
}
```
