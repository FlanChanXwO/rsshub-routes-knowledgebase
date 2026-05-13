# 知乎 - xhu - 话题

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/xhu/topic/:topicId`
- Route Name: `xhu - 话题`
- Example: `/zhihu/xhu/topic/19566035`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/topic.ts`
- Source Module: `() => import('@/routes/zhihu/xhu/topic.ts')`

## Description
_None_

## Parameters
- `topicId`: 话题ID


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
  - `www.zhihu.com/topic/:topicId/:type`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/xhu/topic/19566035",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "xhu/topic.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "module": "() => import('@/routes/zhihu/xhu/topic.ts')",
  "name": "xhu - 话题",
  "parameters": {
    "topicId": "话题ID"
  },
  "path": "/xhu/topic/:topicId",
  "radar": [
    {
      "source": [
        "www.zhihu.com/topic/:topicId/:type"
      ]
    }
  ]
}
```
