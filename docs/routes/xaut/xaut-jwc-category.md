# 西安理工大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `xaut`
- Namespace Name: `西安理工大学`
- Route Path: `/xaut/jwc/:category?`
- Route Name: `教务处`
- Example: `/xaut/jwc/tzgg`
- URL: `www.xaut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `mocusez`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
::: warning
有些内容需使用校园网或 VPN 访问知行网获取
:::

| 通知公告 | 新闻动态 | 规章制度 | 竞赛结果公示 | 竞赛获奖通知 | 竞赛信息 | 公开公示 |
| :------: | :------: | :------: | :----------: | :----------: | :------: | :------: |
|   tzgg   |   xwdt   |   gzzd   |     jggs     |     jsjg     |   jsxx   |   gkgs   |

## Parameters
- `category`: 通知类别，默认为通知公告


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
    "university"
  ],
  "description": "::: warning\n有些内容需使用校园网或 VPN 访问知行网获取\n:::\n\n| 通知公告 | 新闻动态 | 规章制度 | 竞赛结果公示 | 竞赛获奖通知 | 竞赛信息 | 公开公示 |\n| :------: | :------: | :------: | :----------: | :----------: | :------: | :------: |\n|   tzgg   |   xwdt   |   gzzd   |     jggs     |     jsjg     |   jsxx   |   gkgs   |",
  "example": "/xaut/jwc/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "mocusez"
  ],
  "name": "教务处",
  "parameters": {
    "category": "通知类别，默认为通知公告"
  },
  "path": "/jwc/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
