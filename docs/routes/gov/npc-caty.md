# 国家能源局 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/npc/:caty`
- Route Name: `通用`
- Example: `/gov/npc/c183`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `233yeee`
- Source Location: `npc/index.ts`
- Source Module: `() => import('@/routes/gov/npc/index.ts')`

## Description
| 立法 | 监督 | 代表 | 理论 | 权威发布 | 滚动新闻 |
| ---- | ---- | ---- | ---- | -------- | -------- |
| c183 | c184 | c185 | c189 | c12435   | c10134   |

## Parameters
- `caty`: 分类名，支持形如 `http://www.npc.gov.cn/npc/c2/*/` 的网站，传入 npc 之后的参数


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
  - `npc.gov.cn/npc/c2/:caty`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 立法 | 监督 | 代表 | 理论 | 权威发布 | 滚动新闻 |\n| ---- | ---- | ---- | ---- | -------- | -------- |\n| c183 | c184 | c185 | c189 | c12435   | c10134   |",
  "example": "/gov/npc/c183",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "npc/index.ts",
  "maintainers": [
    "233yeee"
  ],
  "module": "() => import('@/routes/gov/npc/index.ts')",
  "name": "通用",
  "parameters": {
    "caty": "分类名，支持形如 `http://www.npc.gov.cn/npc/c2/*/` 的网站，传入 npc 之后的参数"
  },
  "path": "/npc/:caty",
  "radar": [
    {
      "source": [
        "npc.gov.cn/npc/c2/:caty"
      ]
    }
  ]
}
```
