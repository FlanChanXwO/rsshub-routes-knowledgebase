# 即刻 - 圈子

## Coverage
`index-only`

## Route
- Namespace: `jike`
- Namespace Name: `即刻`
- Route Path: `/topic/:id/:showUid?`
- Route Name: `圈子`
- Example: `/jike/topic/556688fae4b00c57d9dd46ee`
- URL: `m.okjike.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod, prnake`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/jike/topic.ts')`

## Description
_None_

## Parameters
- `id`: 圈子 id, 可在即刻 web 端圈子页或 APP 分享出来的圈子页 URL 中找到
- `showUid`: {"description": "是否在内容中显示用户信息，设置为 1 则开启", "options": [{"label": "显示", "value": "1"}]}


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
  - `web.okjike.com/topic/:id`
- `target`: `/topic/:id`
### Rule 2
- `source`:
  - `m.okjike.com/topics/:id`
- `target`: `/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/jike/topic/556688fae4b00c57d9dd46ee",
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
    "DIYgod",
    "prnake"
  ],
  "module": "() => import('@/routes/jike/topic.ts')",
  "name": "圈子",
  "parameters": {
    "id": "圈子 id, 可在即刻 web 端圈子页或 APP 分享出来的圈子页 URL 中找到",
    "showUid": {
      "description": "是否在内容中显示用户信息，设置为 1 则开启",
      "options": [
        {
          "label": "显示",
          "value": "1"
        }
      ]
    }
  },
  "path": "/topic/:id/:showUid?",
  "radar": [
    {
      "source": [
        "web.okjike.com/topic/:id"
      ],
      "target": "/topic/:id"
    },
    {
      "source": [
        "m.okjike.com/topics/:id"
      ],
      "target": "/topic/:id"
    }
  ],
  "view": 1
}
```
