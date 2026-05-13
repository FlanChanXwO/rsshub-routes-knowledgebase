# 品玩 - 用户

## Coverage
`index-only`

## Route
- Namespace: `pingwest`
- Namespace Name: `品玩`
- Route Path: `/user/:uid/:type?/:option?`
- Route Name: `用户`
- Example: `/pingwest/user/7781550877/article`
- URL: `pingwest.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `sanmmm`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/pingwest/user.ts')`

## Description
内容类型

| 文章    | 动态  |
| ------- | ----- |
| article | state |

  参数

  -   `fulltext`，全文输出，例如：`/pingwest/user/7781550877/article/fulltext`

## Parameters
- `uid`: 用户id, 可从用户主页中得到
- `type`: 内容类型, 默认为`article`
- `option`: 参数


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
  - `pingwest.com/user/:uid/:type`
  - `pingwest.com/`
- `target`: `/user/:uid/:type`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "内容类型\n\n| 文章    | 动态  |\n| ------- | ----- |\n| article | state |\n\n  参数\n\n  -   `fulltext`，全文输出，例如：`/pingwest/user/7781550877/article/fulltext`",
  "example": "/pingwest/user/7781550877/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "sanmmm"
  ],
  "module": "() => import('@/routes/pingwest/user.ts')",
  "name": "用户",
  "parameters": {
    "option": "参数",
    "type": "内容类型, 默认为`article`",
    "uid": "用户id, 可从用户主页中得到"
  },
  "path": "/user/:uid/:type?/:option?",
  "radar": [
    {
      "source": [
        "pingwest.com/user/:uid/:type",
        "pingwest.com/"
      ],
      "target": "/user/:uid/:type"
    }
  ]
}
```
