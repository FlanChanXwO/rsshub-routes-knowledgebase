# 一亩三分地 - 帖子

## Coverage
`index-only`

## Route
- Namespace: `1point3acres`
- Namespace Name: `一亩三分地`
- Route Path: `/thread/:type?/:order?`
- Route Name: `帖子`
- Example: `/1point3acres/thread/hot`
- URL: `instant.1point3acres.com/`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `EthanWng97, DIYgod, nczitzk`
- Source Location: `thread.ts`
- Source Module: `() => import('@/routes/1point3acres/thread.ts')`

## Description
分类

| 热门帖子 | 最新帖子 |
| -------- | -------- |
| hot      | new      |

  排序方式

| 最新回复 | 最新发布 |
| -------- | -------- |
|          | post     |

## Parameters
- `type`: 帖子分类, 见下表，默认为 hot，即热门帖子
- `order`: 排序方式，见下表，默认为空，即最新回复


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "分类\n\n| 热门帖子 | 最新帖子 |\n| -------- | -------- |\n| hot      | new      |\n\n  排序方式\n\n| 最新回复 | 最新发布 |\n| -------- | -------- |\n|          | post     |",
  "example": "/1point3acres/thread/hot",
  "location": "thread.ts",
  "maintainers": [
    "EthanWng97",
    "DIYgod",
    "nczitzk"
  ],
  "module": "() => import('@/routes/1point3acres/thread.ts')",
  "name": "帖子",
  "parameters": {
    "order": "排序方式，见下表，默认为空，即最新回复",
    "type": "帖子分类, 见下表，默认为 hot，即热门帖子"
  },
  "path": "/thread/:type?/:order?",
  "url": "instant.1point3acres.com/"
}
```
