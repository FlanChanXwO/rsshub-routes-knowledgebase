# 米哈游 - 米游社 - 官方公告

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/bbs/official/:gids/:type?/:page_size?/:last_id?`
- Route Name: `米游社 - 官方公告`
- Example: `/mihoyo/bbs/official/2/3/20/`
- URL: `genshin.hoyoverse.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `CaoMeiYouRen`
- Source Location: `bbs/official.ts`
- Source Module: `() => import('@/routes/mihoyo/bbs/official.ts')`

## Description
游戏 id

| 崩坏三 | 原神 | 崩坏二 | 未定事件簿 | 星穹铁道 | 绝区零 |
| ------ | ---- | ------ | ---------- | -------- | ------ |
| 1      | 2    | 3      | 4          | 6        | 8      |

  公告类型

| 公告 | 活动 | 资讯 |
| ---- | ---- | ---- |
| 1    | 2    | 3    |

## Parameters
- `gids`: 游戏id
- `type`: 公告类型，默认为 2(即 活动)
- `page_size`: 分页大小，默认为 20
- `last_id`: 跳过的公告数，例如指定为 40 就是从第 40 条公告开始，可用于分页


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
    "game"
  ],
  "description": "游戏 id\n\n| 崩坏三 | 原神 | 崩坏二 | 未定事件簿 | 星穹铁道 | 绝区零 |\n| ------ | ---- | ------ | ---------- | -------- | ------ |\n| 1      | 2    | 3      | 4          | 6        | 8      |\n\n  公告类型\n\n| 公告 | 活动 | 资讯 |\n| ---- | ---- | ---- |\n| 1    | 2    | 3    |",
  "example": "/mihoyo/bbs/official/2/3/20/",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bbs/official.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/mihoyo/bbs/official.ts')",
  "name": "米游社 - 官方公告",
  "parameters": {
    "gids": "游戏id",
    "last_id": "跳过的公告数，例如指定为 40 就是从第 40 条公告开始，可用于分页",
    "page_size": "分页大小，默认为 20 ",
    "type": "公告类型，默认为 2(即 活动)"
  },
  "path": "/bbs/official/:gids/:type?/:page_size?/:last_id?"
}
```
