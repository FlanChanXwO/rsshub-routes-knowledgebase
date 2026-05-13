# 西安交通大学 - 电气学院通知

## Coverage
`index-only`

## Route
- Namespace: `xjtu`
- Namespace Name: `西安交通大学`
- Route Path: `/ee/jzxx/:category?`
- Route Name: `电气学院通知`
- Example: `/xjtu/ee/jzxx/bks`
- URL: `2yuan.xjtu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `riverflows2333`
- Source Location: `ee-jzxx.ts`
- Source Module: `() => import('@/routes/xjtu/ee-jzxx.ts')`

## Description
栏目类型

| 主页 | 本科生 | 研究生 | 科研学术 | 采购招标 | 招聘就业 | 行政办公
| --- | ----- | ----- | ------ | ------- | ------ | ------
|  -  |  bks  |  yjs  |  kyxs  |   cgzb  |  zpjy  | xzbg

## Parameters
- `category`: 类别：`bks`，默认为首页，详情在描述中


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
  - `ee.xjtu.edu.cn/jzxx/:category?.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "栏目类型\n\n| 主页 | 本科生 | 研究生 | 科研学术 | 采购招标 | 招聘就业 | 行政办公\n| --- | ----- | ----- | ------ | ------- | ------ | ------\n|  -  |  bks  |  yjs  |  kyxs  |   cgzb  |  zpjy  | xzbg  ",
  "example": "/xjtu/ee/jzxx/bks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ee-jzxx.ts",
  "maintainers": [
    "riverflows2333"
  ],
  "module": "() => import('@/routes/xjtu/ee-jzxx.ts')",
  "name": "电气学院通知",
  "parameters": {
    "category": "类别：`bks`，默认为首页，详情在描述中"
  },
  "path": "/ee/jzxx/:category?",
  "radar": [
    {
      "source": [
        "ee.xjtu.edu.cn/jzxx/:category?.htm"
      ]
    }
  ]
}
```
