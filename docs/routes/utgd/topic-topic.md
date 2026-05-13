# UNTAG - 专题

## Coverage
`index-only`

## Route
- Namespace: `utgd`
- Namespace Name: `UNTAG`
- Route Path: `/topic/:topic?`
- Route Name: `专题`
- Example: `/utgd/topic/在线阅读专栏`
- URL: `utgd.net/topic`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/utgd/topic.ts')`

## Description
| 在线阅读专栏 | 卡片笔记专题 |
| ------------ | ------------ |

  更多专栏请见 [专题广场](https://utgd.net/topic)

## Parameters
- `topic`: 专题，默认为在线阅读专栏


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
  - `utgd.net/topic`
  - `utgd.net/`
- `target`: `/topic/:topic`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 在线阅读专栏 | 卡片笔记专题 |\n| ------------ | ------------ |\n\n  更多专栏请见 [专题广场](https://utgd.net/topic)",
  "example": "/utgd/topic/在线阅读专栏",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topic.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/utgd/topic.ts')",
  "name": "专题",
  "parameters": {
    "topic": "专题，默认为在线阅读专栏"
  },
  "path": "/topic/:topic?",
  "radar": [
    {
      "source": [
        "utgd.net/topic",
        "utgd.net/"
      ],
      "target": "/topic/:topic"
    }
  ],
  "url": "utgd.net/topic"
}
```
