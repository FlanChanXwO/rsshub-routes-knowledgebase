# Bangumi 番组计划 - 小组话题

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/group/:id`
- Route Name: `小组话题`
- Example: `/bangumi.tv/group/boring`
- URL: `bangumi.tv`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `SettingDust`
- Source Location: `group/topic.ts`
- Source Module: `() => import('@/routes/bangumi.tv/group/topic.ts')`

## Description
_None_

## Parameters
- `id`: 小组 id, 在小组页面地址栏查看


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
  - `bgm.tv/group/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bangumi.tv/group/boring",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "group/topic.ts",
  "maintainers": [
    "SettingDust"
  ],
  "module": "() => import('@/routes/bangumi.tv/group/topic.ts')",
  "name": "小组话题",
  "parameters": {
    "id": "小组 id, 在小组页面地址栏查看"
  },
  "path": "/group/:id",
  "radar": [
    {
      "source": [
        "bgm.tv/group/:id"
      ]
    }
  ]
}
```
