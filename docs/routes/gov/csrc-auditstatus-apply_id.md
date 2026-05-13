# 国家能源局 - 申请事项进度

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/csrc/auditstatus/:apply_id`
- Route Name: `申请事项进度`
- Example: `/gov/csrc/auditstatus/9ce91cf2d750ee62de27fbbcb05fa483`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `hillerliao`
- Source Location: `csrc/auditstatus.ts`
- Source Module: `() => import('@/routes/gov/csrc/auditstatus.ts')`

## Description
_None_

## Parameters
- `apply_id`: 事项类别id，`https://neris.csrc.gov.cn/alappl/home/xkDetail` 列表中各地址的 appMatrCde 参数


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
    "government"
  ],
  "example": "/gov/csrc/auditstatus/9ce91cf2d750ee62de27fbbcb05fa483",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "csrc/auditstatus.ts",
  "maintainers": [
    "hillerliao"
  ],
  "module": "() => import('@/routes/gov/csrc/auditstatus.ts')",
  "name": "申请事项进度",
  "parameters": {
    "apply_id": "事项类别id，`https://neris.csrc.gov.cn/alappl/home/xkDetail` 列表中各地址的 appMatrCde 参数"
  },
  "path": "/csrc/auditstatus/:apply_id"
}
```
