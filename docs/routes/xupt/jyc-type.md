# 西安邮电大学 - 教务处通知公告

## Coverage
`index-only`

## Route
- Namespace: `xupt`
- Namespace Name: `西安邮电大学`
- Route Path: `/jyc/:type?`
- Route Name: `教务处通知公告`
- Example: `/xupt/jyc`
- URL: `xupt.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `StudyingLover`
- Source Location: `jyc.ts`
- Source Module: `() => import('@/routes/xupt/jyc.ts')`

## Description
| 分类 | 参数 |
| ---- | ---- |
| 通知公告 | tzgg |

## Parameters
- `type`: 分类，默认为 tzgg（通知公告）


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
  - `jyc.xupt.edu.cn/index/tzgg.htm`
- `target`: `/jyc/tzgg`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 分类 | 参数 |\n| ---- | ---- |\n| 通知公告 | tzgg |",
  "example": "/xupt/jyc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jyc.ts",
  "maintainers": [
    "StudyingLover"
  ],
  "module": "() => import('@/routes/xupt/jyc.ts')",
  "name": "教务处通知公告",
  "parameters": {
    "type": "分类，默认为 tzgg（通知公告）"
  },
  "path": "/jyc/:type?",
  "radar": [
    {
      "source": [
        "jyc.xupt.edu.cn/index/tzgg.htm"
      ],
      "target": "/jyc/tzgg"
    }
  ]
}
```
