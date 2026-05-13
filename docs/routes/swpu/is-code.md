# 西南石油大学 - 信息学院

## Coverage
`index-only`

## Route
- Namespace: `swpu`
- Namespace Name: `西南石油大学`
- Route Path: `/is/:code`
- Route Name: `信息学院`
- Example: `/swpu/is/xyxw`
- URL: `swpu.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `RiverTwilight`
- Source Location: `is.ts`
- Source Module: `() => import('@/routes/swpu/is.ts')`

## Description
| 栏目 | 学院新闻 | 通知公告 | 教育教学 | 学生工作 | 招生就业 |
| ---- | -------- | -------- | -------- | -------- | -------- |
| 代码 | xyxw     | tzgg     | jyjx     | xsgz     | zsjy     |

## Parameters
- `code`: 栏目代码


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
  - `swpu.edu.cn/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 栏目 | 学院新闻 | 通知公告 | 教育教学 | 学生工作 | 招生就业 |\n| ---- | -------- | -------- | -------- | -------- | -------- |\n| 代码 | xyxw     | tzgg     | jyjx     | xsgz     | zsjy     |",
  "example": "/swpu/is/xyxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "is.ts",
  "maintainers": [
    "RiverTwilight"
  ],
  "module": "() => import('@/routes/swpu/is.ts')",
  "name": "信息学院",
  "parameters": {
    "code": "栏目代码"
  },
  "path": "/is/:code",
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
