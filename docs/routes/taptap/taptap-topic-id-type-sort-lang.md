# TapTap - 游戏论坛

## Coverage
`index-only`

## Route
- Namespace: `taptap`
- Namespace Name: `TapTap`
- Route Path: `/taptap/topic/:id/:type?/:sort?/:lang?`
- Route Name: `游戏论坛`
- Example: `/taptap/topic/142793/official`
- URL: `www.taptap.io`
- Language: `_None_`
- Categories: `game`
- Maintainers: `hoilc, TonyRL`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
| 全部 | 精华  | 官方     | 影片  |
| ---- | ----- | -------- | ----- |
| feed | elite | official | video |

| 发布时间 | 回复时间  | 默认排序 |
| -------- | --------- | -------- |
| created  | commented | default  |

## Parameters
- `id`: 游戏 ID，游戏主页 URL 中获取
- `type`: 论坛版块，默认显示所有帖子，论坛版块 URL 中 `type` 参数，见下表，默认为 `feed`
- `sort`: 排序，见下表，默认为 `created`
- `lang`: 语言，`zh-CN`或`zh-TW`，默认为`zh-CN`


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
  - `taptap.cn/app/:id/topic`
  - `taptap.cn/app/:id`
- `target`: `/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 全部 | 精华  | 官方     | 影片  |\n| ---- | ----- | -------- | ----- |\n| feed | elite | official | video |\n\n| 发布时间 | 回复时间  | 默认排序 |\n| -------- | --------- | -------- |\n| created  | commented | default  |",
  "example": "/taptap/topic/142793/official",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "topic.ts",
  "maintainers": [
    "hoilc",
    "TonyRL"
  ],
  "name": "游戏论坛",
  "parameters": {
    "id": "游戏 ID，游戏主页 URL 中获取",
    "lang": "语言，`zh-CN`或`zh-TW`，默认为`zh-CN`",
    "sort": "排序，见下表，默认为 `created`",
    "type": "论坛版块，默认显示所有帖子，论坛版块 URL 中 `type` 参数，见下表，默认为 `feed`"
  },
  "path": "/topic/:id/:type?/:sort?/:lang?",
  "radar": [
    {
      "source": [
        "taptap.cn/app/:id/topic",
        "taptap.cn/app/:id"
      ],
      "target": "/topic/:id"
    }
  ],
  "topFeeds": [
    {
      "description": "燕云十六声 - 最新 - TapTap 论坛 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "203994880915322880",
      "image": "https://img-tc.tapimg.com/market/images/515c6583cd5cb05f2f343e8b581df575.png",
      "ownerUserId": null,
      "siteUrl": "https://www.taptap.cn/app/239372/topic?type=feed&sort=created",
      "title": "燕云十六声 - 最新 - TapTap 论坛",
      "type": "feed",
      "url": "rsshub://taptap/topic/239372"
    },
    {
      "description": "Phigros - 官方 - TapTap 论坛 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "197299073968664580",
      "image": "https://img-tc.tapimg.com/market/images/9000b8b031deabbd424b7f2f530ee162.png",
      "ownerUserId": null,
      "siteUrl": "https://www.taptap.cn/app/165287/topic?type=official&sort=created",
      "title": "Phigros - 官方 - TapTap 论坛",
      "type": "feed",
      "url": "rsshub://taptap/topic/165287/official"
    }
  ]
}
```
