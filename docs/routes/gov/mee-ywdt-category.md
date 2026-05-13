# 国家能源局 - 要闻动态

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/mee/ywdt/:category?`
- Route Name: `要闻动态`
- Example: `/gov/mee/ywdt/hjywnews`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `liuxsdev`
- Source Location: `mee/ywdt.ts`
- Source Module: `() => import('@/routes/gov/mee/ywdt.ts')`

## Description
| 时政要闻 | 环境要闻 | 地方快讯 | 新闻发布 | 视频新闻 | 公示公告 |
| :------: | :------: | :------: | :------: | :------: | :------: |
|   szyw   | hjywnews |  dfnews  |   xwfb   |   spxw   |   gsgg   |

## Parameters
- `category`: 分类名，预设 `szyw`


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
  - `www.mee.gov.cn/ywdt/:category`
- `target`: `/mee/ywdt/:category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 时政要闻 | 环境要闻 | 地方快讯 | 新闻发布 | 视频新闻 | 公示公告 |\n| :------: | :------: | :------: | :------: | :------: | :------: |\n|   szyw   | hjywnews |  dfnews  |   xwfb   |   spxw   |   gsgg   |",
  "example": "/gov/mee/ywdt/hjywnews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "mee/ywdt.ts",
  "maintainers": [
    "liuxsdev"
  ],
  "module": "() => import('@/routes/gov/mee/ywdt.ts')",
  "name": "要闻动态",
  "parameters": {
    "category": "分类名，预设 `szyw`"
  },
  "path": "/mee/ywdt/:category?",
  "radar": [
    {
      "source": [
        "www.mee.gov.cn/ywdt/:category"
      ],
      "target": "/mee/ywdt/:category"
    }
  ]
}
```
