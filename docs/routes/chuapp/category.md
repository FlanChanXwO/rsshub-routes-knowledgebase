# 触乐 - 分类

## Coverage
`index-only`

## Route
- Namespace: `chuapp`
- Namespace Name: `触乐`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/chuapp/daily`
- URL: `chuapp.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `dousha`
- Source Location: `chuapp.ts`
- Source Module: `() => import('@/routes/chuapp/chuapp.ts')`

## Description
| `category` | 栏目分类 |
  | ------------ | ------- |
  | `daily`    | 每日聚焦 |
  | `pcz`      | 最好玩   |
  | `night`    | 触乐夜话 |
  | `news`     | 动态资讯 |

## Parameters
- `category`: 栏目分类，见下表


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
  - `chuapp.com/category/:category`
- `target`: `/:category`
### Rule 2
- `source`:
  - `chuapp.com/tag/index/id/20369.html`
- `target`: `/night`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "\n  | `category` | 栏目分类 |\n  | ------------ | ------- |\n  | `daily`    | 每日聚焦 |\n  | `pcz`      | 最好玩   |\n  | `night`    | 触乐夜话 |\n  | `news`     | 动态资讯 |\n    ",
  "example": "/chuapp/daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "chuapp.ts",
  "maintainers": [
    "dousha"
  ],
  "module": "() => import('@/routes/chuapp/chuapp.ts')",
  "name": "分类",
  "parameters": {
    "category": "栏目分类，见下表"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "chuapp.com/category/:category"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "chuapp.com/tag/index/id/20369.html"
      ],
      "target": "/night"
    }
  ]
}
```
