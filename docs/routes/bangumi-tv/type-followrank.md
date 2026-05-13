# Bangumi 番组计划 - 成员关注榜

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/:type/followrank`
- Route Name: `成员关注榜`
- Example: `/bangumi.tv/anime/followrank`
- URL: `bangumi.tv`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `honue, zhoukuncheng, NekoAria`
- Source Location: `other/followrank.ts`
- Source Module: `() => import('@/routes/bangumi.tv/other/followrank.ts')`

## Description
_None_

## Parameters
- `type`: 类型：anime - 动画，book - 图书，music - 音乐，game - 游戏，real - 三次元


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
  - `bgm.tv/:type`
- `target`: `/:type/followrank`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bangumi.tv/anime/followrank",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "other/followrank.ts",
  "maintainers": [
    "honue",
    "zhoukuncheng",
    "NekoAria"
  ],
  "module": "() => import('@/routes/bangumi.tv/other/followrank.ts')",
  "name": "成员关注榜",
  "parameters": {
    "type": "类型：anime - 动画，book - 图书，music - 音乐，game - 游戏，real - 三次元"
  },
  "path": "/:type/followrank",
  "radar": [
    {
      "source": [
        "bgm.tv/:type"
      ],
      "target": "/:type/followrank"
    }
  ]
}
```
