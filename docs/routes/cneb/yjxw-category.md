# 中国国家应急广播 - 应急新闻

## Coverage
`index-only`

## Route
- Namespace: `cneb`
- Namespace Name: `中国国家应急广播`
- Route Path: `/yjxw/:category?`
- Route Name: `应急新闻`
- Example: `/cneb/yjxw`
- URL: `cneb.gov.cn`
- Language: `zh-CN`
- Categories: `forecast`
- Maintainers: `nczitzk`
- Source Location: `yjxw.ts`
- Source Module: `() => import('@/routes/cneb/yjxw.ts')`

## Description
| 全部 | 国内新闻 | 国际新闻 |
| ---- | -------- | -------- |
|      | gnxw     | gjxw     |

## Parameters
- `category`: 分类，见下表，默认为全部


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
  - `cneb.gov.cn/yjxw/:category?`
  - `cneb.gov.cn/`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "| 全部 | 国内新闻 | 国际新闻 |\n| ---- | -------- | -------- |\n|      | gnxw     | gjxw     |",
  "example": "/cneb/yjxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yjxw.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/cneb/yjxw.ts')",
  "name": "应急新闻",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/yjxw/:category?",
  "radar": [
    {
      "source": [
        "cneb.gov.cn/yjxw/:category?",
        "cneb.gov.cn/"
      ]
    }
  ]
}
```
