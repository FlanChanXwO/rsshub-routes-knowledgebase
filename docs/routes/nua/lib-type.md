# Nanjing University of the Arts 南京艺术学院 - Library

## Coverage
`index-only`

## Route
- Namespace: `nua`
- Namespace Name: `Nanjing University of the Arts 南京艺术学院`
- Route Path: `/lib/:type`
- Route Name: `Library`
- Example: `/nua/lib/xwdt`
- URL: `index.nua.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `evnydd0sf`
- Source Location: `lib.ts`
- Source Module: `() => import('@/routes/nua/lib.ts')`

## Description
| News Type | Parameters |
| --------- | ---------- |
| 新闻动态  | xwdt       |
| 党建动态  | djdt       |
| 资源动态  | zydt       |
| 服务动态  | fwdt       |

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
  - `lib.nua.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| News Type | Parameters |\n| --------- | ---------- |\n| 新闻动态  | xwdt       |\n| 党建动态  | djdt       |\n| 资源动态  | zydt       |\n| 服务动态  | fwdt       |",
  "example": "/nua/lib/xwdt",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "lib.ts",
  "maintainers": [
    "evnydd0sf"
  ],
  "module": "() => import('@/routes/nua/lib.ts')",
  "name": "Library",
  "parameters": {
    "type": "News Type"
  },
  "path": "/lib/:type",
  "radar": [
    {
      "source": [
        "lib.nua.edu.cn/:type/list.htm"
      ]
    }
  ]
}
```
