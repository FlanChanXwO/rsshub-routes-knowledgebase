# 知乎 - 话题

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/topic/:topicId/:isTop?`
- Route Name: `话题`
- Example: `/zhihu/topic/19828946`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `xyqfer`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/zhihu/topic.ts')`

## Description
_None_

## Parameters
- `topicId`: 话题 id
- `isTop`: 仅精华，默认为否，其他值为是


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES"}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.zhihu.com/topic/:topicId/:type`
- `target`: `/topic/:topicId`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/topic/19828946",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topic.ts",
  "maintainers": [
    "xyqfer"
  ],
  "module": "() => import('@/routes/zhihu/topic.ts')",
  "name": "话题",
  "parameters": {
    "isTop": "仅精华，默认为否，其他值为是",
    "topicId": "话题 id"
  },
  "path": "/topic/:topicId/:isTop?",
  "radar": [
    {
      "source": [
        "www.zhihu.com/topic/:topicId/:type"
      ],
      "target": "/topic/:topicId"
    }
  ]
}
```
