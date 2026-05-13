# 游戏日报 - 分类

## Coverage
`index-only`

## Route
- Namespace: `yxrb`
- Namespace Name: `游戏日报`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/yxrb/info`
- URL: `news.yxrb.net`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `TonyRL`
- Source Location: `home.ts`
- Source Module: `() => import('@/routes/yxrb/home.ts')`

## Description
| 资讯 | 访谈    | 服务    | 游理游据 |
| ---- | ------- | ------- | -------- |
| info | talking | service | comments |

## Parameters
- `category`: 分类，见下表，预设为 `info`


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
  - `news.yxrb.net/:category`
  - `news.yxrb.net/`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 资讯 | 访谈    | 服务    | 游理游据 |\n| ---- | ------- | ------- | -------- |\n| info | talking | service | comments |",
  "example": "/yxrb/info",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "home.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/yxrb/home.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，预设为 `info`"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "news.yxrb.net/:category",
        "news.yxrb.net/"
      ],
      "target": "/:category"
    }
  ]
}
```
