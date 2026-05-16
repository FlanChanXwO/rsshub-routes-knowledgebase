# 米哈游 - 米游社 - 官方公告

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/mihoyo/bbs/official/:gids/:type?/:page_size?/:last_id?`
- Route Name: `米游社 - 官方公告`
- Example: `/mihoyo/bbs/official/2/3/20/`
- URL: `genshin.hoyoverse.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `CaoMeiYouRen`
- Source Location: `bbs/official.ts`
- Source Module: `_None_`

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
  "description": "游戏 id\n\n| 崩坏三 | 原神 | 崩坏二 | 未定事件簿 | 星穹铁道 | 绝区零 |\n| ------ | ---- | ------ | ---------- | -------- | ------ |\n| 1      | 2    | 3      | 4          | 6        | 8      |\n\n公告类型\n\n| 公告 | 活动 | 资讯 |\n| ---- | ---- | ---- |\n| 1    | 2    | 3    |",
  "example": "/mihoyo/bbs/official/2/3/20/",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 168,
  "location": "bbs/official.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "米游社 - 官方公告",
  "parameters": {
    "gids": "游戏id",
    "last_id": "跳过的公告数，例如指定为 40 就是从第 40 条公告开始，可用于分页",
    "page_size": "分页大小，默认为 20 ",
    "type": "公告类型，默认为 2(即 活动)"
  },
  "path": "/bbs/official/:gids/:type?/:page_size?/:last_id?",
  "topFeeds": [
    {
      "description": "米游社 - 原神 - 公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65750657186191360",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.miyoushe.com/ys/home/28?type=1",
      "title": "米游社 - 原神 - 公告",
      "type": "feed",
      "url": "rsshub://mihoyo/bbs/official/2/1/20"
    },
    {
      "description": "米游社 - 崩坏：星穹铁道 - 公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65753799394982912",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.miyoushe.com/sr/home/53?type=1",
      "title": "米游社 - 崩坏：星穹铁道 - 公告",
      "type": "feed",
      "url": "rsshub://mihoyo/bbs/official/6/1/20"
    }
  ]
}
```
