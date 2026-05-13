# Nanjing University of the Arts 南京艺术学院 - Official Information

## Coverage
`index-only`

## Route
- Namespace: `nua`
- Namespace Name: `Nanjing University of the Arts 南京艺术学院`
- Route Path: `/index/:type`
- Route Name: `Official Information`
- Example: `/nua/index/346`
- URL: `index.nua.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `evnydd0sf`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/nua/index.ts')`

## Description
| News Type | Parameters |
| --------- | ---------- |
| 公告      | 346        |
| 南艺要闻  | 332        |

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
  - `index.nua.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| News Type | Parameters |\n| --------- | ---------- |\n| 公告      | 346        |\n| 南艺要闻  | 332        |",
  "example": "/nua/index/346",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "evnydd0sf"
  ],
  "module": "() => import('@/routes/nua/index.ts')",
  "name": "Official Information",
  "parameters": {
    "type": "News Type"
  },
  "path": "/index/:type",
  "radar": [
    {
      "source": [
        "index.nua.edu.cn/:type/list.htm"
      ]
    }
  ]
}
```
