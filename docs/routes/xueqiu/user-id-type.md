# 雪球 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/user/:id/:type?`
- Route Name: `用户动态`
- Example: `/xueqiu/user/8152922548`
- URL: `danjuanapp.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `imlonghao`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/xueqiu/user.ts')`

## Description
| 原发布 | 长文 | 问答 | 热门 | 交易 |
| ------ | ---- | ---- | ---- | ---- |
| 0      | 2    | 4    | 9    | 11   |

## Parameters
- `id`: 用户 id, 可在用户主页 URL 中找到
- `type`: 动态的类型, 不填则默认全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xueqiu.com/u/:id`
- `target`: `/user/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 原发布 | 长文 | 问答 | 热门 | 交易 |\n| ------ | ---- | ---- | ---- | ---- |\n| 0      | 2    | 4    | 9    | 11   |",
  "example": "/xueqiu/user/8152922548",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "imlonghao"
  ],
  "module": "() => import('@/routes/xueqiu/user.ts')",
  "name": "用户动态",
  "parameters": {
    "id": "用户 id, 可在用户主页 URL 中找到",
    "type": "动态的类型, 不填则默认全部"
  },
  "path": "/user/:id/:type?",
  "radar": [
    {
      "source": [
        "xueqiu.com/u/:id"
      ],
      "target": "/user/:id"
    }
  ]
}
```
