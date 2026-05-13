# 游戏打折情报 - 游戏折扣

## Coverage
`index-only`

## Route
- Namespace: `yxdzqb`
- Namespace Name: `游戏打折情报`
- Route Path: `/:type`
- Route Name: `游戏折扣`
- Example: `/yxdzqb/popular_cn`
- URL: `yxdzqb.com/`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `LogicJake, nczitzk`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/yxdzqb/index.tsx')`

## Description
| Steam 最新折扣 | Steam 热门游戏折扣 | Steam 热门中文游戏折扣 | Steam 历史低价 | Steam 中文游戏历史低价 |
| -------------- | ------------------ | ---------------------- | -------------- | ---------------------- |
| discount       | popular            | popular_cn            | low            | low_cn                |

## Parameters
- `type`: 折扣类型


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
  - `yxdzqb.com/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| Steam 最新折扣 | Steam 热门游戏折扣 | Steam 热门中文游戏折扣 | Steam 历史低价 | Steam 中文游戏历史低价 |\n| -------------- | ------------------ | ---------------------- | -------------- | ---------------------- |\n| discount       | popular            | popular_cn            | low            | low_cn                |",
  "example": "/yxdzqb/popular_cn",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "LogicJake",
    "nczitzk"
  ],
  "module": "() => import('@/routes/yxdzqb/index.tsx')",
  "name": "游戏折扣",
  "parameters": {
    "type": "折扣类型"
  },
  "path": "/:type",
  "radar": [
    {
      "source": [
        "yxdzqb.com/"
      ]
    }
  ],
  "url": "yxdzqb.com/"
}
```
