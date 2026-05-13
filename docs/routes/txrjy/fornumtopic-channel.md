# 通信人家园 - 论坛 频道

## Coverage
`index-only`

## Route
- Namespace: `txrjy`
- Namespace Name: `通信人家园`
- Route Path: `/fornumtopic/:channel?`
- Route Name: `论坛 频道`
- Example: `/txrjy/fornumtopic`
- URL: `txrjy.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `Fatpandac`
- Source Location: `fornumtopic.tsx`
- Source Module: `() => import('@/routes/txrjy/fornumtopic.tsx')`

## Description
| 最新 500 个主题帖 | 最新 500 个回复帖 | 最新精华帖 | 最新精华帖 | 一周热帖 | 本月热帖 |
| :---------------: | :---------------: | :--------: | :--------: | :------: | :------: |
|         1         |         2         |      3     |      4     |     5    |     6    |

## Parameters
- `channel`: 频道的 id，见下表，默认为最新500个主题帖


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
  "description": "| 最新 500 个主题帖 | 最新 500 个回复帖 | 最新精华帖 | 最新精华帖 | 一周热帖 | 本月热帖 |\n| :---------------: | :---------------: | :--------: | :--------: | :------: | :------: |\n|         1         |         2         |      3     |      4     |     5    |     6    |",
  "example": "/txrjy/fornumtopic",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "fornumtopic.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/txrjy/fornumtopic.tsx')",
  "name": "论坛 频道",
  "parameters": {
    "channel": "频道的 id，见下表，默认为最新500个主题帖"
  },
  "path": "/fornumtopic/:channel?"
}
```
