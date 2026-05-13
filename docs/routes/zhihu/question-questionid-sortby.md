# 知乎 - 问题

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/question/:questionId/:sortBy?`
- Route Name: `问题`
- Example: `/zhihu/question/59895982`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `None`
- Source Location: `question.ts`
- Source Module: `() => import('@/routes/zhihu/question.ts')`

## Description
_None_

## Parameters
- `questionId`: 问题 id
- `sortBy`: 排序方式：`default`, `created`, `updated`。默认为 `default`


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.zhihu.com/question/:questionId`
- `target`: `/question/:questionId`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/question/59895982",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "question.ts",
  "maintainers": [],
  "module": "() => import('@/routes/zhihu/question.ts')",
  "name": "问题",
  "parameters": {
    "questionId": "问题 id",
    "sortBy": "排序方式：`default`, `created`, `updated`。默认为 `default`"
  },
  "path": "/question/:questionId/:sortBy?",
  "radar": [
    {
      "source": [
        "www.zhihu.com/question/:questionId"
      ],
      "target": "/question/:questionId"
    }
  ]
}
```
