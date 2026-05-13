# 山东大学 - 计算机科学与技术学院通知

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/cs/index/:type?`
- Route Name: `计算机科学与技术学院通知`
- Example: `/sdu/cs/index/announcement`
- URL: `www.sdu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Ji4n1ng, wiketool`
- Source Location: `cs/index.ts`
- Source Module: `() => import('@/routes/sdu/cs/index.ts')`

## Description
| 学院公告 | 学术报告 | 科技简讯 | 本科教育 | 研究生教育 |
| -------- | -------- | -------- | -------- | -------- |
| announcement | academic | technology | undergraduate | postgraduate |

## Parameters
- `type`: 默认为 `announcement`


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
  - `www.cs.sdu.edu.cn/`
  - `www.cs.sdu.edu.cn/xygg.htm`
- `target`: `/cs/index/announcement`
### Rule 2
- `source`:
  - `www.cs.sdu.edu.cn/xsbg.htm`
- `target`: `/cs/index/academic`
### Rule 3
- `source`:
  - `www.cs.sdu.edu.cn/kjjx.htm`
- `target`: `/cs/index/technology`
### Rule 4
- `source`:
  - `www.cs.sdu.edu.cn/bkjy.htm`
- `target`: `/cs/index/undergraduate`
### Rule 5
- `source`:
  - `www.cs.sdu.edu.cn/yjsjy.htm`
- `target`: `/cs/index/postgraduate`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院公告 | 学术报告 | 科技简讯 | 本科教育 | 研究生教育 |\n| -------- | -------- | -------- | -------- | -------- |\n| announcement | academic | technology | undergraduate | postgraduate |",
  "example": "/sdu/cs/index/announcement",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cs/index.ts",
  "maintainers": [
    "Ji4n1ng",
    "wiketool"
  ],
  "module": "() => import('@/routes/sdu/cs/index.ts')",
  "name": "计算机科学与技术学院通知",
  "parameters": {
    "type": "默认为 `announcement`"
  },
  "path": "/cs/index/:type?",
  "radar": [
    {
      "source": [
        "www.cs.sdu.edu.cn/",
        "www.cs.sdu.edu.cn/xygg.htm"
      ],
      "target": "/cs/index/announcement"
    },
    {
      "source": [
        "www.cs.sdu.edu.cn/xsbg.htm"
      ],
      "target": "/cs/index/academic"
    },
    {
      "source": [
        "www.cs.sdu.edu.cn/kjjx.htm"
      ],
      "target": "/cs/index/technology"
    },
    {
      "source": [
        "www.cs.sdu.edu.cn/bkjy.htm"
      ],
      "target": "/cs/index/undergraduate"
    },
    {
      "source": [
        "www.cs.sdu.edu.cn/yjsjy.htm"
      ],
      "target": "/cs/index/postgraduate"
    }
  ]
}
```
