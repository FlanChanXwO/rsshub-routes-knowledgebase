# 国家能源局 - 茂名市茂南区人民政府

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/maonan/:category`
- Route Name: `茂名市茂南区人民政府`
- Example: `/gov/maonan/zwgk`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `ShuiHuo`
- Source Location: `maonan/maonan.ts`
- Source Module: `() => import('@/routes/gov/maonan/maonan.ts')`

## Description
| 政务公开 | 政务新闻 | 茂南动态 | 重大会议 | 公告公示 | 招录信息 | 政策解读 |
| :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|   zwgk   |   zwxw   |   mndt   |   zdhy   |   tzgg   |   zlxx   |   zcjd   |

## Parameters
- `category`: 分类名


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
  "description": "| 政务公开 | 政务新闻 | 茂南动态 | 重大会议 | 公告公示 | 招录信息 | 政策解读 |\n| :------: | :------: | :------: | :------: | :------: | :------: | :------: |\n|   zwgk   |   zwxw   |   mndt   |   zdhy   |   tzgg   |   zlxx   |   zcjd   |",
  "example": "/gov/maonan/zwgk",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "maonan/maonan.ts",
  "maintainers": [
    "ShuiHuo"
  ],
  "module": "() => import('@/routes/gov/maonan/maonan.ts')",
  "name": "茂名市茂南区人民政府",
  "parameters": {
    "category": "分类名"
  },
  "path": "/maonan/:category"
}
```
