# 深圳市罗湖区人民政府 - 今日绵竹

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `深圳市罗湖区人民政府`
- Route Path: `/gov/sichuan/deyang/mztoday/:infoType?`
- Route Name: `今日绵竹`
- Example: `/gov/sichuan/deyang/mztoday/zx`
- URL: `www.mztoday.gov.cn/*`
- Language: `_None_`
- Categories: `government`
- Maintainers: `zytomorrow`
- Source Location: `sichuan/deyang/mztoday.tsx`
- Source Module: `_None_`

## Description
| 最新 | 推荐 | 时政 | 教育 | 民生 | 文旅 | 经济 | 文明创建 | 部门 | 镇（街道） | 健康绵竹 | 南轩讲堂 | 视频 | 文明实践 | 领航中国 | 绵竹年画 | 绵竹历史 | 绵竹旅游 | 外媒看绵竹 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | -------- | ---- | ---------- | -------- | -------- | ---- | -------- | -------- | -------- | -------- | -------- | ---------- |
| zx   | tj   | sz   | jy   | ms   | wl   | jj   | wmcj     | bm   | zj         | jkmz     | nxjt     | sp   | wmsj     | lhzg     | mznh     | mzls     | mzly     | wmkmz      |

## Parameters
- `infoType`: 信息栏目名称。默认最新(zx)


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
  - `www.mztoday.gov.cn/*`
- `target`: `/sichuan/deyang/mztoday`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 最新 | 推荐 | 时政 | 教育 | 民生 | 文旅 | 经济 | 文明创建 | 部门 | 镇（街道） | 健康绵竹 | 南轩讲堂 | 视频 | 文明实践 | 领航中国 | 绵竹年画 | 绵竹历史 | 绵竹旅游 | 外媒看绵竹 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | -------- | ---- | ---------- | -------- | -------- | ---- | -------- | -------- | -------- | -------- | -------- | ---------- |\n| zx   | tj   | sz   | jy   | ms   | wl   | jj   | wmcj     | bm   | zj         | jkmz     | nxjt     | sp   | wmsj     | lhzg     | mznh     | mzls     | mzly     | wmkmz      |",
  "example": "/gov/sichuan/deyang/mztoday/zx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "sichuan/deyang/mztoday.tsx",
  "maintainers": [
    "zytomorrow"
  ],
  "name": "今日绵竹",
  "parameters": {
    "infoType": "信息栏目名称。默认最新(zx)"
  },
  "path": "/sichuan/deyang/mztoday/:infoType?",
  "radar": [
    {
      "source": [
        "www.mztoday.gov.cn/*"
      ],
      "target": "/sichuan/deyang/mztoday"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.mztoday.gov.cn/*"
}
```
