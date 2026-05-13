# 浙江大学 - 软件学院

## Coverage
`index-only`

## Route
- Namespace: `zju`
- Namespace Name: `浙江大学`
- Route Path: `/cst/custom/:id`
- Route Name: `软件学院`
- Example: `/zju/cst/custom/36194+36241+36246`
- URL: `physics.zju.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `zwithz`
- Source Location: `cst/custom.ts`
- Source Module: `() => import('@/routes/zju/cst/custom.ts')`

## Description
| 全部通知 | 招生信息 | 教务管理 | 论文管理 | 思政工作 | 评奖评优 | 实习就业 | 国际实习 | 国内合作科研 | 国际合作科研 | 校园服务 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | ------------ | ------------ | -------- |
| 0        | 1        | 2        | 3        | 4        | 5        | 6        | 7        | 8            | 9            | 10       |

#### 自定义聚合通知 {#zhe-jiang-da-xue-ruan-jian-xue-yuan-zi-ding-yi-ju-he-tong-zhi}

## Parameters
- `id`: 提取出通知页面中的 `ID`，如 `http://www.cst.zju.edu.cn/36246/list.htm` 中的 `36246`，可将你想获取通知的多个页面，通过 `+` 符号来聚合。


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
  "description": "| 全部通知 | 招生信息 | 教务管理 | 论文管理 | 思政工作 | 评奖评优 | 实习就业 | 国际实习 | 国内合作科研 | 国际合作科研 | 校园服务 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | ------------ | ------------ | -------- |\n| 0        | 1        | 2        | 3        | 4        | 5        | 6        | 7        | 8            | 9            | 10       |\n\n#### 自定义聚合通知 {#zhe-jiang-da-xue-ruan-jian-xue-yuan-zi-ding-yi-ju-he-tong-zhi}",
  "example": "/zju/cst/custom/36194+36241+36246",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cst/custom.ts",
  "maintainers": [
    "zwithz"
  ],
  "module": "() => import('@/routes/zju/cst/custom.ts')",
  "name": "软件学院",
  "parameters": {
    "id": "提取出通知页面中的 `ID`，如 `http://www.cst.zju.edu.cn/36246/list.htm` 中的 `36246`，可将你想获取通知的多个页面，通过 `+` 符号来聚合。"
  },
  "path": "/cst/custom/:id"
}
```
