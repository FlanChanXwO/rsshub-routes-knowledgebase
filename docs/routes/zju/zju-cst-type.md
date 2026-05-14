# 浙江大学 - 软件学院

## Coverage
`index-only`

## Route
- Namespace: `zju`
- Namespace Name: `浙江大学`
- Route Path: `/zju/cst/:type`
- Route Name: `软件学院`
- Example: `/zju/cst/0`
- URL: `physics.zju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `yonvenne, zwithz`
- Source Location: `cst/index.ts`
- Source Module: `_None_`

## Description
| 全部通知 | 招生信息 | 教务管理 | 论文管理 | 思政工作 | 评奖评优 | 实习就业 | 国际实习 | 国内合作科研 | 国际合作科研 | 校园服务 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | ------------ | ------------ | -------- |
| 0        | 1        | 2        | 3        | 4        | 5        | 6        | 7        | 8            | 9            | 10       |

## Parameters
- `type`: 分类，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 全部通知 | 招生信息 | 教务管理 | 论文管理 | 思政工作 | 评奖评优 | 实习就业 | 国际实习 | 国内合作科研 | 国际合作科研 | 校园服务 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | ------------ | ------------ | -------- |\n| 0        | 1        | 2        | 3        | 4        | 5        | 6        | 7        | 8            | 9            | 10       |",
  "example": "/zju/cst/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "cst/index.ts",
  "maintainers": [
    "yonvenne",
    "zwithz"
  ],
  "name": "软件学院",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/cst/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "浙大软件学院-实习就业 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "168412841482685440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cst.zju.edu.cn/36233/list.htm",
      "title": "浙大软件学院-实习就业",
      "type": "feed",
      "url": "rsshub://zju/cst/6"
    },
    {
      "description": "浙大软件学院-国际实习 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "168412983866723328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cst.zju.edu.cn/36235/list.htm",
      "title": "浙大软件学院-国际实习",
      "type": "feed",
      "url": "rsshub://zju/cst/7"
    }
  ]
}
```
