# 浙江大学 - 控制学院通知

## Coverage
`index-only`

## Route
- Namespace: `zju`
- Namespace Name: `浙江大学`
- Route Path: `/cse/:category?`
- Route Name: `控制学院通知`
- Example: `/zju/cse/bksjy`
- URL: `physics.zju.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Rabbits-sys`
- Source Location: `cse/index.ts`
- Source Module: `() => import('@/routes/zju/cse/index.ts')`

## Description
栏目类型

| 简讯专栏 | 本科生教育 | 研究生教育 | 科研学术 | 人事工作 | 学生思政 | 对外交流 | 就业指导 |
| ------ | ------- | ------- | ------ | ------ | ------ | ------ | ------ |
|   -    |  bksjy  |  yjsjy  |  kyxs  |  rsgz  |  xssz  |  dwjl  |  jyzd  |

## Parameters
- `category`: 类别：`bksjy`，默认为简讯专栏，详情在描述中


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
  "description": "栏目类型\n\n| 简讯专栏 | 本科生教育 | 研究生教育 | 科研学术 | 人事工作 | 学生思政 | 对外交流 | 就业指导 |\n| ------ | ------- | ------- | ------ | ------ | ------ | ------ | ------ |\n|   -    |  bksjy  |  yjsjy  |  kyxs  |  rsgz  |  xssz  |  dwjl  |  jyzd  |",
  "example": "/zju/cse/bksjy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cse/index.ts",
  "maintainers": [
    "Rabbits-sys"
  ],
  "module": "() => import('@/routes/zju/cse/index.ts')",
  "name": "控制学院通知",
  "parameters": {
    "category": "类别：`bksjy`，默认为简讯专栏，详情在描述中"
  },
  "path": "/cse/:category?"
}
```
