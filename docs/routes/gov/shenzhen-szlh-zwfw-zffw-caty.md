# 国家能源局 - 深圳市罗湖区人民政府

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/shenzhen/szlh/zwfw/zffw/:caty`
- Route Name: `深圳市罗湖区人民政府`
- Example: `/gov/shenzhen/szlh/zwfw/zffw/tzgg`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `lonn`
- Source Location: `shenzhen/szlh/index.ts`
- Source Module: `() => import('@/routes/gov/shenzhen/szlh/index.ts')`

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
  - `szlh.gov.cn/zwfw/zffw/:caty`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告 |\n| :------: |\n|   tzgg   |",
  "example": "/gov/shenzhen/szlh/zwfw/zffw/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "shenzhen/szlh/index.ts",
  "maintainers": [
    "lonn"
  ],
  "module": "() => import('@/routes/gov/shenzhen/szlh/index.ts')",
  "name": "深圳市罗湖区人民政府",
  "parameters": {
    "caty": "信息类别"
  },
  "path": "/shenzhen/szlh/zwfw/zffw/:caty",
  "radar": [
    {
      "source": [
        "szlh.gov.cn/zwfw/zffw/:caty"
      ]
    }
  ]
}
```
