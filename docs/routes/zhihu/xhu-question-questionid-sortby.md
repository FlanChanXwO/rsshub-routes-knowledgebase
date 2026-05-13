# 知乎 - xhu - 问题

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/xhu/question/:questionId/:sortBy?`
- Route Name: `xhu - 问题`
- Example: `/zhihu/xhu/question/264051433`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/question.ts`
- Source Module: `() => import('@/routes/zhihu/xhu/question.ts')`

## Description
_None_

## Parameters
- `questionId`: 问题 id
- `sortBy`: 排序方式：`default`, `created`, `updated`。默认为 `default`


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
  - `www.zhihu.com/question/:questionId`
- `target`: `/xhu/question/:questionId`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/xhu/question/264051433",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "xhu/question.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "module": "() => import('@/routes/zhihu/xhu/question.ts')",
  "name": "xhu - 问题",
  "parameters": {
    "questionId": "问题 id",
    "sortBy": "排序方式：`default`, `created`, `updated`。默认为 `default`"
  },
  "path": "/xhu/question/:questionId/:sortBy?",
  "radar": [
    {
      "source": [
        "www.zhihu.com/question/:questionId"
      ],
      "target": "/xhu/question/:questionId"
    }
  ]
}
```
