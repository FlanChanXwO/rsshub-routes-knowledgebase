# 深圳大学 - 研究生招生网

## Coverage
`index-only`

## Route
- Namespace: `szu`
- Namespace Name: `深圳大学`
- Route Path: `/yz/:type?`
- Route Name: `研究生招生网`
- Example: `/szu/yz/1`
- URL: `yz.szu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `NagaruZ`
- Source Location: `yz/index.ts`
- Source Module: `() => import('@/routes/szu/yz/index.ts')`

## Description
| 研究生 | 博士生 |
| ------ | ------ |
| 1      | 2      |

## Parameters
- `type`: 默认为 `1`


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
    "university"
  ],
  "description": "| 研究生 | 博士生 |\n| ------ | ------ |\n| 1      | 2      |",
  "example": "/szu/yz/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yz/index.ts",
  "maintainers": [
    "NagaruZ"
  ],
  "module": "() => import('@/routes/szu/yz/index.ts')",
  "name": "研究生招生网",
  "parameters": {
    "type": "默认为 `1`"
  },
  "path": "/yz/:type?"
}
```
