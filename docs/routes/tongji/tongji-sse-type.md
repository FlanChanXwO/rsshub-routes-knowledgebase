# 同济大学 - 软件学院通知

## Coverage
`index-only`

## Route
- Namespace: `tongji`
- Namespace Name: `同济大学`
- Route Path: `/tongji/sse/:type?`
- Route Name: `软件学院通知`
- Example: `/tongji/sse/xytz`
- URL: `bksy.tongji.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `sgqy`
- Source Location: `sse/notice.ts`
- Source Module: `_None_`

## Description
| 本科生通知 | 研究生通知 | 教工通知 | 全体通知 | 学院通知 | 学院新闻 | 学院活动 |
| ---------- | ---------- | -------- | -------- | -------- | -------- | -------- |
| bkstz      | yjstz      | jgtz     | qttz     | xytz     | xyxw     | xyhd     |

注意: `qttz` 与 `xytz` 在原网站等价.

## Parameters
- `type`: 通知类型，默认为 `xytz`


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
  "description": "| 本科生通知 | 研究生通知 | 教工通知 | 全体通知 | 学院通知 | 学院新闻 | 学院活动 |\n| ---------- | ---------- | -------- | -------- | -------- | -------- | -------- |\n| bkstz      | yjstz      | jgtz     | qttz     | xytz     | xyxw     | xyhd     |\n\n注意: `qttz` 与 `xytz` 在原网站等价.",
  "example": "/tongji/sse/xytz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "sse/notice.ts",
  "maintainers": [
    "sgqy"
  ],
  "name": "软件学院通知",
  "parameters": {
    "type": "通知类型，默认为 `xytz`"
  },
  "path": "/sse/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
