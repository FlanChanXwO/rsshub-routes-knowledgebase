# 中国科学技术大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `ustc`
- Namespace Name: `中国科学技术大学`
- Route Path: `/gs/:type?`
- Route Name: `研究生院`
- Example: `/ustc/gs/tzgg`
- URL: `gradschool.ustc.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `jasongzy`
- Source Location: `gs.ts`
- Source Module: `() => import('@/routes/ustc/gs.ts')`

## Description
| 通知公告 | 新闻动态 |
| -------- | -------- |
| tzgg     | xwdt     |

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
  - `gradschool.ustc.edu.cn/`
- `target`: `/gs`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 新闻动态 |\n| -------- | -------- |\n| tzgg     | xwdt     |",
  "example": "/ustc/gs/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gs.ts",
  "maintainers": [
    "jasongzy"
  ],
  "module": "() => import('@/routes/ustc/gs.ts')",
  "name": "研究生院",
  "parameters": {
    "type": "分类，见下表，默认为通知公告"
  },
  "path": "/gs/:type?",
  "radar": [
    {
      "source": [
        "gradschool.ustc.edu.cn/"
      ],
      "target": "/gs"
    }
  ],
  "url": "gradschool.ustc.edu.cn/"
}
```
