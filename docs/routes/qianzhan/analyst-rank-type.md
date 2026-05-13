# 前瞻网 - 排行榜

## Coverage
`index-only`

## Route
- Namespace: `qianzhan`
- Namespace Name: `前瞻网`
- Route Path: `/analyst/rank/:type?`
- Route Name: `排行榜`
- Example: `/qianzhan/analyst/rank/week`
- URL: `qianzhan.com/analyst`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `moke8`
- Source Location: `rank.ts`
- Source Module: `() => import('@/routes/qianzhan/rank.ts')`

## Description
| 周排行 | 月排行 |
| ------ | ------ |
| week   | month  |

## Parameters
- `type`: 分类，见下表


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
  - `qianzhan.com/analyst`
  - `qianzhan.com/`
- `target`: `/analyst/rank`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 周排行 | 月排行 |\n| ------ | ------ |\n| week   | month  |",
  "example": "/qianzhan/analyst/rank/week",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "rank.ts",
  "maintainers": [
    "moke8"
  ],
  "module": "() => import('@/routes/qianzhan/rank.ts')",
  "name": "排行榜",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/analyst/rank/:type?",
  "radar": [
    {
      "source": [
        "qianzhan.com/analyst",
        "qianzhan.com/"
      ],
      "target": "/analyst/rank"
    }
  ],
  "url": "qianzhan.com/analyst"
}
```
