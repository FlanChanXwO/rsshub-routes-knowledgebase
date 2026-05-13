# 牛客网 - 讨论区

## Coverage
`index-only`

## Route
- Namespace: `nowcoder`
- Namespace Name: `牛客网`
- Route Path: `/discuss/:type/:order`
- Route Name: `讨论区`
- Example: `/nowcoder/discuss/2/4`
- URL: `nowcoder.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `LogicJake`
- Source Location: `discuss.ts`
- Source Module: `() => import('@/routes/nowcoder/discuss.ts')`

## Description
| 最新回复 | 最新发表 | 最新 | 精华 |
| -------- | -------- | ---- | ---- |
| 0        | 3        | 1    | 4    |

## Parameters
- `type`: 讨论区分区id 在 URL 中可以找到
- `order`: 排序方式


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
    "bbs"
  ],
  "description": "| 最新回复 | 最新发表 | 最新 | 精华 |\n| -------- | -------- | ---- | ---- |\n| 0        | 3        | 1    | 4    |",
  "example": "/nowcoder/discuss/2/4",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "discuss.ts",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/nowcoder/discuss.ts')",
  "name": "讨论区",
  "parameters": {
    "order": "排序方式",
    "type": "讨论区分区id 在 URL 中可以找到"
  },
  "path": "/discuss/:type/:order"
}
```
