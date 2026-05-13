# 国家能源局 - 深圳市人民政府

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/shenzhen/xxgk/zfxxgj/:caty`
- Route Name: `深圳市人民政府`
- Example: `/gov/shenzhen/xxgk/zfxxgj/tzgg`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `laoxua`
- Source Location: `shenzhen/xxgk/zfxxgj.ts`
- Source Module: `() => import('@/routes/gov/shenzhen/xxgk/zfxxgj.ts')`

## Description
| 通知公告 | 政府采购 | 资金信息 | 重大项目 |
| :------: | :------: | :------: | :------: |
|   tzgg   |   zfcg   |   zjxx   |   zdxm   |

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
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告 | 政府采购 | 资金信息 | 重大项目 |\n| :------: | :------: | :------: | :------: |\n|   tzgg   |   zfcg   |   zjxx   |   zdxm   |",
  "example": "/gov/shenzhen/xxgk/zfxxgj/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "shenzhen/xxgk/zfxxgj.ts",
  "maintainers": [
    "laoxua"
  ],
  "module": "() => import('@/routes/gov/shenzhen/xxgk/zfxxgj.ts')",
  "name": "深圳市人民政府",
  "parameters": {
    "caty": "信息类别"
  },
  "path": "/shenzhen/xxgk/zfxxgj/:caty"
}
```
