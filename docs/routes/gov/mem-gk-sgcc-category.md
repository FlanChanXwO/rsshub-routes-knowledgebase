# 国家能源局 - 事故及灾害查处

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/mem/gk/sgcc/:category?`
- Route Name: `事故及灾害查处`
- Example: `/gov/mem/gk/sgcc/tbzdsgdcbg`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `mem/sgcc.ts`
- Source Module: `() => import('@/routes/gov/mem/sgcc.ts')`

## Description
| 挂牌督办 | 调查报告   |
| -------- | ---------- |
| sggpdbqk | tbzdsgdcbg |

## Parameters
- `category`: 分类，见下表，默认为挂牌督办


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
  - `www.mem.gov.cn/gk/sgcc/:category`
- `target`: `/mem/gk/sgcc/:category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 挂牌督办 | 调查报告   |\n| -------- | ---------- |\n| sggpdbqk | tbzdsgdcbg |",
  "example": "/gov/mem/gk/sgcc/tbzdsgdcbg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "mem/sgcc.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gov/mem/sgcc.ts')",
  "name": "事故及灾害查处",
  "parameters": {
    "category": "分类，见下表，默认为挂牌督办"
  },
  "path": "/mem/gk/sgcc/:category?",
  "radar": [
    {
      "source": [
        "www.mem.gov.cn/gk/sgcc/:category"
      ],
      "target": "/mem/gk/sgcc/:category"
    }
  ]
}
```
