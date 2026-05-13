# 微博 - 超话

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/super_index/:id/:type?/:routeParams?`
- Route Name: `超话`
- Example: `/weibo/super_index/1008084989d223732bf6f02f75ea30efad58a9/sort_time`
- URL: `weibo.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `zengxs, Rongronggg9`
- Source Location: `super-index.ts`
- Source Module: `() => import('@/routes/weibo/super-index.ts')`

## Description
| type       | 备注             |
| ---------- | ---------------- |
| soul       | 精华             |
| video      | 视频（暂不支持） |
| album      | 相册（暂不支持） |
| hot_sort  | 热门             |
| sort_time | 最新帖子         |
| feed       | 最新评论         |

## Parameters
- `id`: 超话ID
- `type`: 类型：见下表
- `routeParams`: 额外参数；请参阅上面的说明和表格


## Features
- `requireConfig`: [{"description": "", "name": "WEIBO_COOKIES", "optional": true}]
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `weibo.com/p/:id/super_index`
- `target`: `/super_index/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "| type       | 备注             |\n| ---------- | ---------------- |\n| soul       | 精华             |\n| video      | 视频（暂不支持） |\n| album      | 相册（暂不支持） |\n| hot_sort  | 热门             |\n| sort_time | 最新帖子         |\n| feed       | 最新评论         |",
  "example": "/weibo/super_index/1008084989d223732bf6f02f75ea30efad58a9/sort_time",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "WEIBO_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "super-index.ts",
  "maintainers": [
    "zengxs",
    "Rongronggg9"
  ],
  "module": "() => import('@/routes/weibo/super-index.ts')",
  "name": "超话",
  "parameters": {
    "id": "超话ID",
    "routeParams": "额外参数；请参阅上面的说明和表格",
    "type": "类型：见下表"
  },
  "path": "/super_index/:id/:type?/:routeParams?",
  "radar": [
    {
      "source": [
        "weibo.com/p/:id/super_index"
      ],
      "target": "/super_index/:id"
    }
  ]
}
```
