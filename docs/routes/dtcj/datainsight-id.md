# DT 财经 - 数据洞察

## Coverage
`index-only`

## Route
- Namespace: `dtcj`
- Namespace Name: `DT 财经`
- Route Path: `/datainsight/:id?`
- Route Name: `数据洞察`
- Example: `/dtcj/datainsight`
- URL: `dtcj.com/dtcj/datainsight`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `datainsight.ts`
- Source Module: `() => import('@/routes/dtcj/datainsight.ts')`

## Description
| 城数 | NEXT 情报局 | 专业精选 |
| ---- | ----------- | -------- |
| 3    | 1           | 4        |

## Parameters
- `id`: 分类，见下表，默认为全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `dtcj.com/insighttopic/:id`
- `target`: `/datainsight/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 城数 | NEXT 情报局 | 专业精选 |\n| ---- | ----------- | -------- |\n| 3    | 1           | 4        |",
  "example": "/dtcj/datainsight",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "datainsight.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/dtcj/datainsight.ts')",
  "name": "数据洞察",
  "parameters": {
    "id": "分类，见下表，默认为全部"
  },
  "path": "/datainsight/:id?",
  "radar": [
    {
      "source": [
        "dtcj.com/insighttopic/:id"
      ],
      "target": "/datainsight/:id"
    }
  ],
  "url": "dtcj.com/dtcj/datainsight"
}
```
