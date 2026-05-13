# InfoQ 中文 - 话题

## Coverage
`index-only`

## Route
- Namespace: `infoq`
- Namespace Name: `InfoQ 中文`
- Route Path: `/topic/:id`
- Route Name: `话题`
- Example: `/infoq/topic/1`
- URL: `infoq.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `brilon`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/infoq/topic.ts')`

## Description
_None_

## Parameters
- `id`: 话题id，可在 [InfoQ全部话题](https://www.infoq.cn/topics) 页面找到URL里的话题id


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
  - `infoq.cn/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/infoq/topic/1",
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
    "brilon"
  ],
  "module": "() => import('@/routes/infoq/topic.ts')",
  "name": "话题",
  "parameters": {
    "id": "话题id，可在 [InfoQ全部话题](https://www.infoq.cn/topics) 页面找到URL里的话题id"
  },
  "path": "/topic/:id",
  "radar": [
    {
      "source": [
        "infoq.cn/topic/:id"
      ]
    }
  ]
}
```
