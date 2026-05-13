# 福建考试报名网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `fjksbm`
- Namespace Name: `福建考试报名网`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/fjksbm`
- URL: `fjksbm.com`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/fjksbm/index.ts')`

## Description
| 已发布公告 (方案)，即将开始 | 网络报名进行中 | 网络报名结束等待打印准考证 | 正在打印准考证 | 考试结束，等待发布成绩 | 已发布成绩 | 新闻动态 | 政策法规 |
| --------------------------- | -------------- | -------------------------- | -------------- | ---------------------- | ---------- | -------- | -------- |
| 0                           | 1              | 2                          | 3              | 4                      | 5          | news     | policy   |

## Parameters
- `category`: 分类，见下表，默认为网络报名进行中


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
  - `fjksbm.com/portal/:category?`
  - `fjksbm.com/portal`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| 已发布公告 (方案)，即将开始 | 网络报名进行中 | 网络报名结束等待打印准考证 | 正在打印准考证 | 考试结束，等待发布成绩 | 已发布成绩 | 新闻动态 | 政策法规 |\n| --------------------------- | -------------- | -------------------------- | -------------- | ---------------------- | ---------- | -------- | -------- |\n| 0                           | 1              | 2                          | 3              | 4                      | 5          | news     | policy   |",
  "example": "/fjksbm",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/fjksbm/index.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为网络报名进行中"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "fjksbm.com/portal/:category?",
        "fjksbm.com/portal"
      ]
    }
  ]
}
```
