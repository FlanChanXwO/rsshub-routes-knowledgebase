# ASMR Online - 最新收录

## Coverage
`index-only`

## Route
- Namespace: `asmr-200`
- Namespace Name: `ASMR Online`
- Route Path: `/works/:order?/:subtitle?/:sort?`
- Route Name: `最新收录`
- Example: `/asmr-200/works`
- URL: `asmr-200.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `hualiong`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/asmr-200/index.tsx')`

## Description
| 发售日期 | 收录日期 | 销量 | 价格 | 评价 | 随机 | RJ号 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| release | create_date | dl_count | price | rate_average_2dp | random | id |

## Parameters
- `order`: 排序字段，默认按照资源的收录日期来排序，详见下表
- `sort`: 排序方式，可选 `asc` 和 `desc` ，默认倒序
- `subtitle`: 筛选带字幕音频，可选 `0` 和 `1` ，默认关闭


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `asmr-200.com`
- `target`: `asmr-200/works`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| 发售日期 | 收录日期 | 销量 | 价格 | 评价 | 随机 | RJ号 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| release | create_date | dl_count | price | rate_average_2dp | random | id |",
  "example": "/asmr-200/works",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "hualiong"
  ],
  "module": "() => import('@/routes/asmr-200/index.tsx')",
  "name": "最新收录",
  "parameters": {
    "order": "排序字段，默认按照资源的收录日期来排序，详见下表",
    "sort": "排序方式，可选 `asc` 和 `desc` ，默认倒序",
    "subtitle": "筛选带字幕音频，可选 `0` 和 `1` ，默认关闭"
  },
  "path": "/works/:order?/:subtitle?/:sort?",
  "radar": [
    {
      "source": [
        "asmr-200.com"
      ],
      "target": "asmr-200/works"
    }
  ],
  "url": "asmr-200.com"
}
```
