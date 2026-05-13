# China Jiliang University - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `cjlu`
- Namespace Name: `China Jiliang University`
- Route Path: `/yjsy/:cate`
- Route Name: `研究生院`
- Example: `/cjlu/yjsy/yjstz`
- URL: `www.cjlu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `chrisis58`
- Source Location: `yjsy/index.ts`
- Source Module: `() => import('@/routes/cjlu/yjsy/index.ts')`

## Description
| 研究生通知 | 教师通知 |
| -------- | -------- |
| yjstz    | jstz     |

## Parameters
- `cate`: {"default": "yjstz", "description": "订阅的类型，支持 yjstz（研究生通知）和 jstz（教师通知）", "options": [{"label": "教师通知", "value": "jstz"}, {"label": "研究生通知", "value": "yjstz"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `研究生通知`
- `source`:
  - `yjsy.cjlu.edu.cn/index/yjstz/:suffix`
  - `yjsy.cjlu.edu.cn/index/yjstz.htm`
- `target`: `/yjsy/yjstz`
### Rule 2
- `title`: `教师通知`
- `source`:
  - `yjsy.cjlu.edu.cn/index/jstz/:suffix`
  - `yjsy.cjlu.edu.cn/index/jstz.htm`
- `target`: `/yjsy/jstz`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 研究生通知 | 教师通知 |\n| -------- | -------- |\n| yjstz    | jstz     |",
  "example": "/cjlu/yjsy/yjstz",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "yjsy/index.ts",
  "maintainers": [
    "chrisis58"
  ],
  "module": "() => import('@/routes/cjlu/yjsy/index.ts')",
  "name": "研究生院",
  "parameters": {
    "cate": {
      "default": "yjstz",
      "description": "订阅的类型，支持 yjstz（研究生通知）和 jstz（教师通知）",
      "options": [
        {
          "label": "教师通知",
          "value": "jstz"
        },
        {
          "label": "研究生通知",
          "value": "yjstz"
        }
      ]
    }
  },
  "path": "/yjsy/:cate",
  "radar": [
    {
      "source": [
        "yjsy.cjlu.edu.cn/index/yjstz/:suffix",
        "yjsy.cjlu.edu.cn/index/yjstz.htm"
      ],
      "target": "/yjsy/yjstz",
      "title": "研究生通知"
    },
    {
      "source": [
        "yjsy.cjlu.edu.cn/index/jstz/:suffix",
        "yjsy.cjlu.edu.cn/index/jstz.htm"
      ],
      "target": "/yjsy/jstz",
      "title": "教师通知"
    }
  ]
}
```
