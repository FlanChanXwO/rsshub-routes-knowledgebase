# 国家能源局 - 电视剧政务平台

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/nrta/dsj/:category?`
- Route Name: `电视剧政务平台`
- Example: `/gov/nrta/dsj`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `nrta/dsj.ts`
- Source Module: `() => import('@/routes/gov/nrta/dsj.ts')`

## Description
| 备案公示 | 发行许可通告 | 重大题材立项     | 重大题材摄制    | 变更通报 |
| -------- | ------------ | ---------------- | --------------- | -------- |
| note     | announce     | importantLixiang | importantShezhi | changing |

## Parameters
- `category`: 分类，见下表，默认为备案公示


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "description": "| 备案公示 | 发行许可通告 | 重大题材立项     | 重大题材摄制    | 变更通报 |\n| -------- | ------------ | ---------------- | --------------- | -------- |\n| note     | announce     | importantLixiang | importantShezhi | changing |",
  "example": "/gov/nrta/dsj",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "nrta/dsj.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gov/nrta/dsj.ts')",
  "name": "电视剧政务平台",
  "parameters": {
    "category": "分类，见下表，默认为备案公示"
  },
  "path": "/nrta/dsj/:category?"
}
```
