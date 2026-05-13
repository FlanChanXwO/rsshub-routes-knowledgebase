# 山东大学 - 计算机科学与技术学院通知

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/sdu/cs/index/:type?`
- Route Name: `计算机科学与技术学院通知`
- Example: `/sdu/cs/index/announcement`
- URL: `www.sdu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Ji4n1ng, wiketool`
- Source Location: `cs/index.ts`
- Source Module: `_None_`

## Description
| 学院公告     | 学术报告 | 科技简讯   | 本科教育      | 研究生教育   |
| ------------ | -------- | ---------- | ------------- | ------------ |
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
  "description": "| 学院公告     | 学术报告 | 科技简讯   | 本科教育      | 研究生教育   |\n| ------------ | -------- | ---------- | ------------- | ------------ |\n| announcement | academic | technology | undergraduate | postgraduate |",
  "example": "/sdu/cs/index/announcement",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cs/index.ts",
  "maintainers": [
    "Ji4n1ng",
    "wiketool"
  ],
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
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:567:9)\n    at processTimers (node:internal/timers:541:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
