# 东南大学 - 研究生招生网通知公告

## Coverage
`index-only`

## Route
- Namespace: `seu`
- Namespace Name: `东南大学`
- Route Path: `/yzb/:type`
- Route Name: `研究生招生网通知公告`
- Example: `/seu/yzb/6676`
- URL: `cse.seu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `fuzy112`
- Source Location: `yzb/index.ts`
- Source Module: `() => import('@/routes/seu/yzb/index.ts')`

## Description
| 硕士招生 | 博士招生 | 港澳台及中外合作办学 |
| -------- | -------- | -------------------- |
| 6676     | 6677     | 6679                 |

## Parameters
- `type`: 分类名，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `yzb.seu.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 硕士招生 | 博士招生 | 港澳台及中外合作办学 |\n| -------- | -------- | -------------------- |\n| 6676     | 6677     | 6679                 |",
  "example": "/seu/yzb/6676",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yzb/index.ts",
  "maintainers": [
    "fuzy112"
  ],
  "module": "() => import('@/routes/seu/yzb/index.ts')",
  "name": "研究生招生网通知公告",
  "parameters": {
    "type": "分类名，见下表"
  },
  "path": "/yzb/:type",
  "radar": [
    {
      "source": [
        "yzb.seu.edu.cn/:type/list.htm"
      ]
    }
  ]
}
```
