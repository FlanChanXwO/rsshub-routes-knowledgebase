# 西南石油大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `swpu`
- Namespace Name: `西南石油大学`
- Route Path: `/dean/:code`
- Route Name: `教务处`
- Example: `/swpu/dean/tzgg`
- URL: `swpu.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `CYTMWIA`
- Source Location: `dean.ts`
- Source Module: `() => import('@/routes/swpu/dean.ts')`

## Description
| 栏目 | 通知公告 | 新闻报道 | 视点声音 |
| ---- | -------- | -------- | -------- |
| 代码 | tzgg     | xwbd     | sdsy     |

## Parameters
- `code`: 栏目代码


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `swpu.edu.cn/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 栏目 | 通知公告 | 新闻报道 | 视点声音 |\n| ---- | -------- | -------- | -------- |\n| 代码 | tzgg     | xwbd     | sdsy     |",
  "example": "/swpu/dean/tzgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dean.ts",
  "maintainers": [
    "CYTMWIA"
  ],
  "module": "() => import('@/routes/swpu/dean.ts')",
  "name": "教务处",
  "parameters": {
    "code": "栏目代码"
  },
  "path": "/dean/:code",
  "radar": [
    {
      "source": [
        "swpu.edu.cn/"
      ],
      "target": ""
    }
  ],
  "url": "swpu.edu.cn/"
}
```
