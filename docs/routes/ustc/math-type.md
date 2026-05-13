# 中国科学技术大学 - 数学科学学院

## Coverage
`index-only`

## Route
- Namespace: `ustc`
- Namespace Name: `中国科学技术大学`
- Route Path: `/math/:type?`
- Route Name: `数学科学学院`
- Example: `/ustc/math/tzgg`
- URL: `math.ustc.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ne0-wu`
- Source Location: `math.ts`
- Source Module: `() => import('@/routes/ustc/math.ts')`

## Description
| 学院新闻 | 通知公告 | 学术交流 | 学术报告 |
| -------- | -------- | -------- | -------- |
| xyxw     | tzgg     | xsjl     | xsbg     |

## Parameters
- `type`: 分类，见下表，默认为通知公告


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
  - `math.ustc.edu.cn/`
- `target`: `/math`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院新闻 | 通知公告 | 学术交流 | 学术报告 |\n| -------- | -------- | -------- | -------- |\n| xyxw     | tzgg     | xsjl     | xsbg     |",
  "example": "/ustc/math/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "math.ts",
  "maintainers": [
    "ne0-wu"
  ],
  "module": "() => import('@/routes/ustc/math.ts')",
  "name": "数学科学学院",
  "parameters": {
    "type": "分类，见下表，默认为通知公告"
  },
  "path": "/math/:type?",
  "radar": [
    {
      "source": [
        "math.ustc.edu.cn/"
      ],
      "target": "/math"
    }
  ],
  "url": "math.ustc.edu.cn/"
}
```
