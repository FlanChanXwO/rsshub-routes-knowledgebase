# 西南石油大学 - 计算机与软件学院

## Coverage
`index-only`

## Route
- Namespace: `swpu`
- Namespace Name: `西南石油大学`
- Route Path: `/scs/:code`
- Route Name: `计算机与软件学院`
- Example: `/swpu/scs/tzgg`
- URL: `swpu.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `CYTMWIA`
- Source Location: `scs.ts`
- Source Module: `() => import('@/routes/swpu/scs.ts')`

## Description
| 栏目 | 通知公告 | 新闻速递 |
| ---- | -------- | -------- |
| 代码 | tzgg     | xwsd     |

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
  "description": "| 栏目 | 通知公告 | 新闻速递 |\n| ---- | -------- | -------- |\n| 代码 | tzgg     | xwsd     |",
  "example": "/swpu/scs/tzgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "scs.ts",
  "maintainers": [
    "CYTMWIA"
  ],
  "module": "() => import('@/routes/swpu/scs.ts')",
  "name": "计算机与软件学院",
  "parameters": {
    "code": "栏目代码"
  },
  "path": "/scs/:code",
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
