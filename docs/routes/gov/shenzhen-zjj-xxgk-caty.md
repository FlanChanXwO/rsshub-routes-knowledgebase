# 国家能源局 - 深圳市住房和建设局

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/shenzhen/zjj/xxgk/:caty`
- Route Name: `深圳市住房和建设局`
- Example: `/gov/shenzhen/zjj/xxgk/tzgg`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `lonn`
- Source Location: `shenzhen/zjj/index.ts`
- Source Module: `() => import('@/routes/gov/shenzhen/zjj/index.ts')`

## Description
| 通知公告 |
| :------: |
|   tzgg   |

## Parameters
- `caty`: 信息类别


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
  - `zjj.sz.gov.cn/xxgk/:caty`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告 |\n| :------: |\n|   tzgg   |",
  "example": "/gov/shenzhen/zjj/xxgk/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "shenzhen/zjj/index.ts",
  "maintainers": [
    "lonn"
  ],
  "module": "() => import('@/routes/gov/shenzhen/zjj/index.ts')",
  "name": "深圳市住房和建设局",
  "parameters": {
    "caty": "信息类别"
  },
  "path": "/shenzhen/zjj/xxgk/:caty",
  "radar": [
    {
      "source": [
        "zjj.sz.gov.cn/xxgk/:caty"
      ]
    }
  ]
}
```
