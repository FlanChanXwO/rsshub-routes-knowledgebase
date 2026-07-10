# 电子科技大学 - 文化素质教育中心

## Coverage
`index-only`

## Route
- Namespace: `uestc`
- Namespace Name: `电子科技大学`
- Route Path: `/uestc/cqe/:type?`
- Route Name: `文化素质教育中心`
- Example: `/uestc/cqe/tzgg`
- URL: `cqe.uestc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `truobel, mobyw`
- Source Location: `cqe.ts`
- Source Module: `_None_`

## Description
| 活动预告 | 通知公告 |
| -------- | -------- |
| hdyg     | tzgg     |

## Parameters
- `type`: 默认为 `tzgg`


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cqe.uestc.edu.cn/`
- `target`: `/cqe`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 活动预告 | 通知公告 |\n| -------- | -------- |\n| hdyg     | tzgg     |",
  "example": "/uestc/cqe/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cqe.ts",
  "maintainers": [
    "truobel",
    "mobyw"
  ],
  "name": "文化素质教育中心",
  "parameters": {
    "type": "默认为 `tzgg`"
  },
  "path": "/cqe/:type?",
  "radar": [
    {
      "source": [
        "cqe.uestc.edu.cn/"
      ],
      "target": "/cqe"
    }
  ],
  "topFeeds": [],
  "url": "cqe.uestc.edu.cn/"
}
```
