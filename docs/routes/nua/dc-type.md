# Nanjing University of the Arts 南京艺术学院 - School of Design

## Coverage
`index-only`

## Route
- Namespace: `nua`
- Namespace Name: `Nanjing University of the Arts 南京艺术学院`
- Route Path: `/dc/:type`
- Route Name: `School of Design`
- Example: `/nua/dc/news`
- URL: `index.nua.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `evnydd0sf`
- Source Location: `dc.ts`
- Source Module: `() => import('@/routes/nua/dc.ts')`

## Description
| News Type                | Parameters |
| ------------------------ | ---------- |
| 学院新闻 NEWS            | news       |
| 展览 EXHIBITION          | exhibition |
| 研创 RESEARCH & CREATION | rc         |
| 项目 PROJECT             | project    |
| 党团 PARTY               | party      |
| 后浪 YOUTH               | youth      |

## Parameters
- `type`: News Type


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
  - `dc.nua.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| News Type                | Parameters |\n| ------------------------ | ---------- |\n| 学院新闻 NEWS            | news       |\n| 展览 EXHIBITION          | exhibition |\n| 研创 RESEARCH & CREATION | rc         |\n| 项目 PROJECT             | project    |\n| 党团 PARTY               | party      |\n| 后浪 YOUTH               | youth      |",
  "example": "/nua/dc/news",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dc.ts",
  "maintainers": [
    "evnydd0sf"
  ],
  "module": "() => import('@/routes/nua/dc.ts')",
  "name": "School of Design",
  "parameters": {
    "type": "News Type"
  },
  "path": "/dc/:type",
  "radar": [
    {
      "source": [
        "dc.nua.edu.cn/:type/list.htm"
      ]
    }
  ]
}
```
