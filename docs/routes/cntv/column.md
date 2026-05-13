# CNTV - 栏目

## Coverage
`index-only`

## Route
- Namespace: `cntv`
- Namespace Name: `CNTV`
- Route Path: `/:column`
- Route Name: `栏目`
- Example: `/cntv/TOPC1451528971114112`
- URL: `navi.cctv.com/`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `WhoIsSure, Fatpandac`
- Source Location: `column.tsx`
- Source Module: `() => import('@/routes/cntv/column.tsx')`

## Description
::: tip
栏目 ID 查找示例:
打开栏目具体某一期页面，F12 控制台输入`column_id`得到栏目 ID。
:::

  栏目

| 新闻联播             | 新闻周刊             | 天下足球             |
| -------------------- | -------------------- | -------------------- |
| TOPC1451528971114112 | TOPC1451559180488841 | TOPC1451551777876756 |

## Parameters
- `column`: 栏目ID, 可在对应CNTV栏目页面找到


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
  - `navi.cctv.com/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n栏目 ID 查找示例:\n打开栏目具体某一期页面，F12 控制台输入`column_id`得到栏目 ID。\n:::\n\n  栏目\n\n| 新闻联播             | 新闻周刊             | 天下足球             |\n| -------------------- | -------------------- | -------------------- |\n| TOPC1451528971114112 | TOPC1451559180488841 | TOPC1451551777876756 |",
  "example": "/cntv/TOPC1451528971114112",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "column.tsx",
  "maintainers": [
    "WhoIsSure",
    "Fatpandac"
  ],
  "module": "() => import('@/routes/cntv/column.tsx')",
  "name": "栏目",
  "parameters": {
    "column": "栏目ID, 可在对应CNTV栏目页面找到"
  },
  "path": "/:column",
  "radar": [
    {
      "source": [
        "navi.cctv.com/"
      ]
    }
  ],
  "url": "navi.cctv.com/"
}
```
