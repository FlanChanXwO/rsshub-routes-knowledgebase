# 西安理工大学 - 学校主页

## Coverage
`index-only`

## Route
- Namespace: `xaut`
- Namespace Name: `西安理工大学`
- Route Path: `/xaut/index/:category?`
- Route Name: `学校主页`
- Example: `/xaut/index/tzgg`
- URL: `www.xaut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `mocusez`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 学校新闻 | 砥志研思 | 立德树人 | 传道授业 | 校闻周知 |
| :------: | :------: | :------: | :------: | :------: |
|   xxxw   |   dzys   |   ldsr   |   cdsy   |   xwzz   |

## Parameters
- `category`: 通知类别，默认为学校新闻


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
  "description": "| 学校新闻 | 砥志研思 | 立德树人 | 传道授业 | 校闻周知 |\n| :------: | :------: | :------: | :------: | :------: |\n|   xxxw   |   dzys   |   ldsr   |   cdsy   |   xwzz   |",
  "example": "/xaut/index/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "mocusez"
  ],
  "name": "学校主页",
  "parameters": {
    "category": "通知类别，默认为学校新闻"
  },
  "path": "/index/:category?",
  "topFeeds": []
}
```
