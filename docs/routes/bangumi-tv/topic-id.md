# Bangumi 番组计划 - 小组话题的新回复

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/topic/:id`
- Route Name: `小组话题的新回复`
- Example: `/bangumi.tv/topic/367032`
- URL: `bangumi.tv`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `ylc395`
- Source Location: `group/reply.ts`
- Source Module: `() => import('@/routes/bangumi.tv/group/reply.ts')`

## Description
_None_

## Parameters
- `id`: 话题 id, 在话题页面地址栏查看


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
  - `bgm.tv/group/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bangumi.tv/topic/367032",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "group/reply.ts",
  "maintainers": [
    "ylc395"
  ],
  "module": "() => import('@/routes/bangumi.tv/group/reply.ts')",
  "name": "小组话题的新回复",
  "parameters": {
    "id": "话题 id, 在话题页面地址栏查看"
  },
  "path": "/topic/:id",
  "radar": [
    {
      "source": [
        "bgm.tv/group/topic/:id"
      ]
    }
  ]
}
```
