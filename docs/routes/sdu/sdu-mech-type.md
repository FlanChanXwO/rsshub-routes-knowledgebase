# 山东大学 - 机械工程学院通知

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/sdu/mech/:type?`
- Route Name: `机械工程学院通知`
- Example: `/sdu/mech/0`
- URL: `www.sdu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Ji4n1ng`
- Source Location: `mech.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 院所新闻 | 教学信息 | 学术动态 | 学院简报 |
| -------- | -------- | -------- | -------- | -------- |
| 0        | 1        | 2        | 3        | 4        |

## Parameters
- `type`: 默认为 `0`


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
  "description": "| 通知公告 | 院所新闻 | 教学信息 | 学术动态 | 学院简报 |\n| -------- | -------- | -------- | -------- | -------- |\n| 0        | 1        | 2        | 3        | 4        |",
  "example": "/sdu/mech/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "mech.ts",
  "maintainers": [
    "Ji4n1ng"
  ],
  "name": "机械工程学院通知",
  "parameters": {
    "type": "默认为 `0`"
  },
  "path": "/mech/:type?",
  "topFeeds": []
}
```
