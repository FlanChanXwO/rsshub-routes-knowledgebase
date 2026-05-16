# 吉首大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `jsu`
- Namespace Name: `吉首大学`
- Route Path: `/jsu/jwc/:types?`
- Route Name: `教务处`
- Example: `/jsu/jwc/jwdt`
- URL: `jsu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `wenjia03`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 教务通知 | 教务动态 |
| -------- | -------- |
| jwtz     | jwdt     |

## Parameters
- `types`: 通知分类 默认为`jwtz`


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
  "description": "| 教务通知 | 教务动态 |\n| -------- | -------- |\n| jwtz     | jwdt     |",
  "example": "/jsu/jwc/jwdt",
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
    "wenjia03"
  ],
  "name": "教务处",
  "parameters": {
    "types": "通知分类 默认为`jwtz`"
  },
  "path": "/jwc/:types?",
  "topFeeds": []
}
```
