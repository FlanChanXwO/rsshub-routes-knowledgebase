# 浙江大学 - 外国语学院

## Coverage
`index-only`

## Route
- Namespace: `zju`
- Namespace Name: `浙江大学`
- Route Path: `/sis/:type`
- Route Name: `外国语学院`
- Example: `/zju/sis/0`
- URL: `www.sis.zju.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Alex222222222222`
- Source Location: `sis/index.ts`
- Source Module: `() => import('@/routes/zju/sis/index.ts')`

## Description
| 重要公告 | 最新通知 | 教育教学 | 科学研究 | 新闻动态 | 联系我们 | 党政管理 | 组织人事 | 科学研究 | 本科教育 | 研究生教育 | 学生思政 | 校友联络 | 对外交流 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 0        | 1        | 2        | 3        | 4        | 5        | 6        | 7            | 8            | 9       | 10       | 11       | 12       | 13       |

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
  "description": "| 重要公告 | 最新通知 | 教育教学 | 科学研究 | 新闻动态 | 联系我们 | 党政管理 | 组织人事 | 科学研究 | 本科教育 | 研究生教育 | 学生思政 | 校友联络 | 对外交流 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| 0        | 1        | 2        | 3        | 4        | 5        | 6        | 7            | 8            | 9       | 10       | 11       | 12       | 13       |\n",
  "example": "/zju/sis/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "sis/index.ts",
  "maintainers": [
    "Alex222222222222"
  ],
  "module": "() => import('@/routes/zju/sis/index.ts')",
  "name": "外国语学院",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/sis/:type",
  "url": "www.sis.zju.edu.cn"
}
```
