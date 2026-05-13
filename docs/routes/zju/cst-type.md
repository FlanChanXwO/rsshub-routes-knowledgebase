# 浙江大学 - 软件学院

## Coverage
`index-only`

## Route
- Namespace: `zju`
- Namespace Name: `浙江大学`
- Route Path: `/cst/:type`
- Route Name: `软件学院`
- Example: `/zju/cst/0`
- URL: `physics.zju.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `yonvenne, zwithz`
- Source Location: `cst/index.ts`
- Source Module: `() => import('@/routes/zju/cst/index.ts')`

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
  "location": "cst/index.ts",
  "maintainers": [
    "yonvenne",
    "zwithz"
  ],
  "module": "() => import('@/routes/zju/cst/index.ts')",
  "name": "软件学院",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/cst/:type"
}
```
