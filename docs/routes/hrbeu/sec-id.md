# 哈尔滨工程大学 - 船舶工程学院

## Coverage
`index-only`

## Route
- Namespace: `hrbeu`
- Namespace Name: `哈尔滨工程大学`
- Route Path: `/sec/:id`
- Route Name: `船舶工程学院`
- Example: `/hrbeu/sec/xshd`
- URL: `yjsy.hrbeu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Chi-hong22`
- Source Location: `sec/list.ts`
- Source Module: `() => import('@/routes/hrbeu/sec/list.ts')`

## Description
| 学院要闻 | 学术活动 | 通知公告 | 学科方向 |
| :------: | :------: |:------: | :------: |
|   xyyw   |   xshd   |  229   |   xkfx   |

## Parameters
- `id`: 栏目编号，由 `URL` 中获取。


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
  - `sec.hrbeu.edu.cn/:id/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院要闻 | 学术活动 | 通知公告 | 学科方向 |\n| :------: | :------: |:------: | :------: |\n|   xyyw   |   xshd   |  229   |   xkfx   |",
  "example": "/hrbeu/sec/xshd",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "sec/list.ts",
  "maintainers": [
    "Chi-hong22"
  ],
  "module": "() => import('@/routes/hrbeu/sec/list.ts')",
  "name": "船舶工程学院",
  "parameters": {
    "id": "栏目编号，由 `URL` 中获取。"
  },
  "path": "/sec/:id",
  "radar": [
    {
      "source": [
        "sec.hrbeu.edu.cn/:id/list.htm"
      ]
    }
  ]
}
```
