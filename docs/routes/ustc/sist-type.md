# 中国科学技术大学 - 信息科学技术学院

## Coverage
`index-only`

## Route
- Namespace: `ustc`
- Namespace Name: `中国科学技术大学`
- Route Path: `/sist/:type?`
- Route Name: `信息科学技术学院`
- Example: `/ustc/sist/tzgg`
- URL: `sist.ustc.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `jasongzy`
- Source Location: `sist.ts`
- Source Module: `() => import('@/routes/ustc/sist.ts')`

## Description
| 通知公告 | 招生工作 |
| -------- | -------- |
| tzgg     | zsgz     |

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
  - `sist.ustc.edu.cn/`
- `target`: `/sist`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 招生工作 |\n| -------- | -------- |\n| tzgg     | zsgz     |",
  "example": "/ustc/sist/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "sist.ts",
  "maintainers": [
    "jasongzy"
  ],
  "module": "() => import('@/routes/ustc/sist.ts')",
  "name": "信息科学技术学院",
  "parameters": {
    "type": "分类，见下表，默认为通知公告"
  },
  "path": "/sist/:type?",
  "radar": [
    {
      "source": [
        "sist.ustc.edu.cn/"
      ],
      "target": "/sist"
    }
  ],
  "url": "sist.ustc.edu.cn/"
}
```
