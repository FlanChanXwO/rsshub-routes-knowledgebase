# 西南石油大学 - 办公网

## Coverage
`index-only`

## Route
- Namespace: `swpu`
- Namespace Name: `西南石油大学`
- Route Path: `/bgw/:code`
- Route Name: `办公网`
- Example: `/swpu/bgw/zytzgg`
- URL: `swpu.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `CYTMWIA`
- Source Location: `bgw.ts`
- Source Module: `() => import('@/routes/swpu/bgw.ts')`

## Description
| 栏目 | 重要通知公告 | 部门通知公告 | 本周活动 |
| ---- | ------------ | ------------ | -------- |
| 代码 | zytzgg       | bmtzgg       | bzhd     |

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
  "description": "| 栏目 | 重要通知公告 | 部门通知公告 | 本周活动 |\n| ---- | ------------ | ------------ | -------- |\n| 代码 | zytzgg       | bmtzgg       | bzhd     |",
  "example": "/swpu/bgw/zytzgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bgw.ts",
  "maintainers": [
    "CYTMWIA"
  ],
  "module": "() => import('@/routes/swpu/bgw.ts')",
  "name": "办公网",
  "parameters": {
    "code": "栏目代码"
  },
  "path": "/bgw/:code",
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
