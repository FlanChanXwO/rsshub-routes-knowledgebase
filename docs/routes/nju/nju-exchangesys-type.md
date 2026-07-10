# 南京大学 - 本科生交换生系统

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/nju/exchangesys/:type`
- Route Name: `本科生交换生系统`
- Example: `/nju/exchangesys/proj`
- URL: `admission.nju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `None`
- Source Location: `exchangesys.ts`
- Source Module: `_None_`

## Description
| 新闻通知 | 交换生项目 |
| -------- | ---------- |
| news     | proj       |

## Parameters
- `type`: 分类名


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
  "description": "| 新闻通知 | 交换生项目 |\n| -------- | ---------- |\n| news     | proj       |",
  "example": "/nju/exchangesys/proj",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "exchangesys.ts",
  "maintainers": [],
  "name": "本科生交换生系统",
  "parameters": {
    "type": "分类名"
  },
  "path": "/exchangesys/:type",
  "topFeeds": []
}
```
