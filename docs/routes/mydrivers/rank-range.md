# 快科技 - 排行

## Coverage
`index-only`

## Route
- Namespace: `mydrivers`
- Namespace Name: `快科技`
- Route Path: `/rank/:range?`
- Route Name: `排行`
- Example: `/mydrivers/rank`
- URL: `m.mydrivers.com/newsclass.aspx`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `rank.ts`
- Source Module: `() => import('@/routes/mydrivers/rank.ts')`

## Description
| 24 小时最热 | 本周最热 | 本月最热 |
| ----------- | -------- | -------- |
| 0           | 1        | 2        |

## Parameters
- `range`: 时间范围，见下表，默认为24小时最热


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
  - `m.mydrivers.com/newsclass.aspx`
- `target`: `/rank`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 24 小时最热 | 本周最热 | 本月最热 |\n| ----------- | -------- | -------- |\n| 0           | 1        | 2        |",
  "example": "/mydrivers/rank",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/mydrivers/rank.ts')",
  "name": "排行",
  "parameters": {
    "range": "时间范围，见下表，默认为24小时最热"
  },
  "path": "/rank/:range?",
  "radar": [
    {
      "source": [
        "m.mydrivers.com/newsclass.aspx"
      ],
      "target": "/rank"
    }
  ],
  "url": "m.mydrivers.com/newsclass.aspx"
}
```
