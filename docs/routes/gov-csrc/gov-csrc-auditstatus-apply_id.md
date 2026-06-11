# 中国证券监督管理委员会 - 申请事项进度

## Coverage
`index-only`

## Route
- Namespace: `gov/csrc`
- Namespace Name: `中国证券监督管理委员会`
- Route Path: `/gov/csrc/auditstatus/:apply_id`
- Route Name: `申请事项进度`
- Example: `/gov/csrc/auditstatus/9ce91cf2d750ee62de27fbbcb05fa483`
- URL: `www.csrc.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `hillerliao`
- Source Location: `auditstatus.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "auditstatus.ts",
  "maintainers": [
    "hillerliao"
  ],
  "name": "申请事项进度",
  "parameters": {
    "apply_id": "事项类别id，`https://neris.csrc.gov.cn/alappl/home/xkDetail` 列表中各地址的 appMatrCde 参数"
  },
  "path": "/auditstatus/:apply_id",
  "topFeeds": []
}
```
