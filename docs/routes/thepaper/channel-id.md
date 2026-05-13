# 澎湃新闻 - 频道

## Coverage
`index-only`

## Route
- Namespace: `thepaper`
- Namespace Name: `澎湃新闻`
- Route Path: `/channel/:id`
- Route Name: `频道`
- Example: `/thepaper/channel/25950`
- URL: `thepaper.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `xyqfer, nczitzk, bigfei`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/thepaper/channel.ts')`

## Description
| 频道 ID | 频道名 |
| ------- | ------ |
| 26916   | 视频   |
| 108856  | 战疫   |
| 25950   | 时事   |
| 25951   | 财经   |
| 36079   | 澎湃号 |
| 119908  | 科技   |
| 25952   | 思想   |
| 119489  | 智库   |
| 25953   | 生活   |
| 26161   | 问吧   |
| 122908  | 国际   |
| -21     | 体育   |
| -24     | 评论   |

## Parameters
- `id`: 频道 id，可在频道页 URL 中找到


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
    "new-media"
  ],
  "description": "| 频道 ID | 频道名 |\n| ------- | ------ |\n| 26916   | 视频   |\n| 108856  | 战疫   |\n| 25950   | 时事   |\n| 25951   | 财经   |\n| 36079   | 澎湃号 |\n| 119908  | 科技   |\n| 25952   | 思想   |\n| 119489  | 智库   |\n| 25953   | 生活   |\n| 26161   | 问吧   |\n| 122908  | 国际   |\n| -21     | 体育   |\n| -24     | 评论   |",
  "example": "/thepaper/channel/25950",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "channel.ts",
  "maintainers": [
    "xyqfer",
    "nczitzk",
    "bigfei"
  ],
  "module": "() => import('@/routes/thepaper/channel.ts')",
  "name": "频道",
  "parameters": {
    "id": "频道 id，可在频道页 URL 中找到"
  },
  "path": "/channel/:id"
}
```
