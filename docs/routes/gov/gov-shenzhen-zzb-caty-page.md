# 国家能源局 - 深圳市委组织部

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/gov/shenzhen/zzb/:caty/:page?`
- Route Name: `深圳市委组织部`
- Example: `/gov/shenzhen/zzb/tzgg`
- URL: `zzb.sz.gov.cn/*`
- Language: `_None_`
- Categories: `government`
- Maintainers: `zlasd`
- Source Location: `shenzhen/zzb/index.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 任前公示 | 政策法规 | 工作动态 | 部门预算决算公开 | 业务表格下载 |
| :------: | :------: | :------: | :------: | :--------------: | :----------: |
|   tzgg   |   rqgs   |   zcfg   |   gzdt   |       xcbd       |     bgxz     |

## Parameters
- `caty`: 信息类别
- `page`: 页码


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
  - `zzb.sz.gov.cn/*`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告 | 任前公示 | 政策法规 | 工作动态 | 部门预算决算公开 | 业务表格下载 |\n| :------: | :------: | :------: | :------: | :--------------: | :----------: |\n|   tzgg   |   rqgs   |   zcfg   |   gzdt   |       xcbd       |     bgxz     |",
  "example": "/gov/shenzhen/zzb/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "shenzhen/zzb/index.ts",
  "maintainers": [
    "zlasd"
  ],
  "name": "深圳市委组织部",
  "parameters": {
    "caty": "信息类别",
    "page": "页码"
  },
  "path": "/shenzhen/zzb/:caty/:page?",
  "radar": [
    {
      "source": [
        "zzb.sz.gov.cn/*"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "zzb.sz.gov.cn/*"
}
```
