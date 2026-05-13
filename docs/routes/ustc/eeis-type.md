# 中国科学技术大学 - 电子工程与信息科学系

## Coverage
`index-only`

## Route
- Namespace: `ustc`
- Namespace Name: `中国科学技术大学`
- Route Path: `/eeis/:type?`
- Route Name: `电子工程与信息科学系`
- Example: `/ustc/eeis/tzgg`
- URL: `eeis.ustc.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `jasongzy`
- Source Location: `eeis.ts`
- Source Module: `() => import('@/routes/ustc/eeis.ts')`

## Description
| 通知公告 | 新闻信息 |
| -------- | -------- |
| tzgg     | xwxx     |

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
  - `eeis.ustc.edu.cn/`
- `target`: `/eeis`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 新闻信息 |\n| -------- | -------- |\n| tzgg     | xwxx     |",
  "example": "/ustc/eeis/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "eeis.ts",
  "maintainers": [
    "jasongzy"
  ],
  "module": "() => import('@/routes/ustc/eeis.ts')",
  "name": "电子工程与信息科学系",
  "parameters": {
    "type": "分类，见下表，默认为通知公告"
  },
  "path": "/eeis/:type?",
  "radar": [
    {
      "source": [
        "eeis.ustc.edu.cn/"
      ],
      "target": "/eeis"
    }
  ],
  "url": "eeis.ustc.edu.cn/"
}
```
