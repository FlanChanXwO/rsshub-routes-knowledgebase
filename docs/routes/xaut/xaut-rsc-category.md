# 西安理工大学 - 人事处

## Coverage
`index-only`

## Route
- Namespace: `xaut`
- Namespace Name: `西安理工大学`
- Route Path: `/xaut/rsc/:category?`
- Route Name: `人事处`
- Example: `/xaut/rsc/tzgg`
- URL: `www.xaut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `mocusez, light0926`
- Source Location: `rsc.ts`
- Source Module: `_None_`

## Description
::: warning
有些内容指向外部链接，目前只提供这些链接，不提供具体内容，去除 jwc 和 index 的修改
:::

| 通知公告 | 工作动态 |
| :------: | :------: |
|   tzgg   |   gzdt   |

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
  "description": "::: warning\n有些内容指向外部链接，目前只提供这些链接，不提供具体内容，去除 jwc 和 index 的修改\n:::\n\n| 通知公告 | 工作动态 |\n| :------: | :------: |\n|   tzgg   |   gzdt   |",
  "example": "/xaut/rsc/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "rsc.ts",
  "maintainers": [
    "mocusez",
    "light0926"
  ],
  "name": "人事处",
  "parameters": {
    "category": "通知类别，默认为通知公告"
  },
  "path": "/rsc/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
