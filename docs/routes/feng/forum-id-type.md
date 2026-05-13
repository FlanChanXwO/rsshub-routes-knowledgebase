# 威锋 - 社区

## Coverage
`index-only`

## Route
- Namespace: `feng`
- Namespace Name: `威锋`
- Route Path: `/forum/:id/:type?`
- Route Name: `社区`
- Example: `/feng/forum/1`
- URL: `feng.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `forum.tsx`
- Source Module: `() => import('@/routes/feng/forum.tsx')`

## Description
| 最新回复 | 最新发布 | 热门 | 精华    |
| -------- | -------- | ---- | ------- |
| newest   | all      | hot  | essence |

## Parameters
- `id`: 版块 ID，可在版块 URL 找到
- `type`: 排序，见下表，默认为 `all`


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
  - `feng.com/forum/photo/:id`
  - `feng.com/forum/:id`
- `target`: `/forum/:id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| 最新回复 | 最新发布 | 热门 | 精华    |\n| -------- | -------- | ---- | ------- |\n| newest   | all      | hot  | essence |",
  "example": "/feng/forum/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "forum.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/feng/forum.tsx')",
  "name": "社区",
  "parameters": {
    "id": "版块 ID，可在版块 URL 找到",
    "type": "排序，见下表，默认为 `all`"
  },
  "path": "/forum/:id/:type?",
  "radar": [
    {
      "source": [
        "feng.com/forum/photo/:id",
        "feng.com/forum/:id"
      ],
      "target": "/forum/:id"
    }
  ]
}
```
