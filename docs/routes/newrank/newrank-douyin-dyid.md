# 新榜 - 抖音短视频

## Coverage
`index-only`

## Route
- Namespace: `newrank`
- Namespace Name: `新榜`
- Route Path: `/newrank/douyin/:dyid`
- Route Name: `抖音短视频`
- Example: `/newrank/douyin/110266463747`
- URL: `newrank.cn`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `lessmoe`
- Source Location: `douyin.ts`
- Source Module: `_None_`

## Description
::: warning
免费版账户抖音每天查询次数 20 次，如需增加次数可购买新榜会员或等待未来多账户支持
:::

## Parameters
- `dyid`: 抖音ID，可在新榜账号详情 URL 中找到


## Features
- `requireConfig`: [{"description": "", "name": "NEWRANK_COOKIE"}]
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
    "social-media"
  ],
  "description": "::: warning\n免费版账户抖音每天查询次数 20 次，如需增加次数可购买新榜会员或等待未来多账户支持\n:::",
  "example": "/newrank/douyin/110266463747",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "NEWRANK_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "douyin.ts",
  "maintainers": [
    "lessmoe"
  ],
  "name": "抖音短视频",
  "parameters": {
    "dyid": "抖音ID，可在新榜账号详情 URL 中找到"
  },
  "path": "/douyin/:dyid",
  "topFeeds": []
}
```
