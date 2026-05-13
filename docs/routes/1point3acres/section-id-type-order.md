# 一亩三分地 - 分区

## Coverage
`index-only`

## Route
- Namespace: `1point3acres`
- Namespace Name: `一亩三分地`
- Route Path: `/section/:id?/:type?/:order?`
- Route Name: `分区`
- Example: `/1point3acres/section/345`
- URL: `blog.1point3acres.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `section.ts`
- Source Module: `() => import('@/routes/1point3acres/section.ts')`

## Description
分区

| 分区     | id  |
| -------- | --- |
| 留学申请 | 257 |
| 世界公民 | 379 |
| 投资理财 | 400 |
| 生活干货 | 31  |
| 职场达人 | 345 |
| 人际关系 | 391 |
| 海外求职 | 38  |
| 签证移民 | 265 |

  分类

| 热门帖子 | 最新帖子 |
| -------- | -------- |
| hot      | new      |

  排序方式

| 最新回复 | 最新发布 |
| -------- | -------- |
|          | post     |

## Parameters
- `id`: 分区 id，见下表，默认为全部
- `type`: 帖子分类, 见下表，默认为 hot，即热门帖子
- `order`: 排序方式，见下表，默认为空，即最新回复


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
  - `instant.1point3acres.com/section/:id`
  - `instant.1point3acres.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "分区\n\n| 分区     | id  |\n| -------- | --- |\n| 留学申请 | 257 |\n| 世界公民 | 379 |\n| 投资理财 | 400 |\n| 生活干货 | 31  |\n| 职场达人 | 345 |\n| 人际关系 | 391 |\n| 海外求职 | 38  |\n| 签证移民 | 265 |\n\n  分类\n\n| 热门帖子 | 最新帖子 |\n| -------- | -------- |\n| hot      | new      |\n\n  排序方式\n\n| 最新回复 | 最新发布 |\n| -------- | -------- |\n|          | post     |",
  "example": "/1point3acres/section/345",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "section.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/1point3acres/section.ts')",
  "name": "分区",
  "parameters": {
    "id": "分区 id，见下表，默认为全部",
    "order": "排序方式，见下表，默认为空，即最新回复",
    "type": "帖子分类, 见下表，默认为 hot，即热门帖子"
  },
  "path": "/section/:id?/:type?/:order?",
  "radar": [
    {
      "source": [
        "instant.1point3acres.com/section/:id",
        "instant.1point3acres.com/"
      ]
    }
  ]
}
```
