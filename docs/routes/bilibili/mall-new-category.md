# 哔哩哔哩 bilibili - 会员购新品上架

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/mall/new/:category?`
- Route Name: `会员购新品上架`
- Example: `/bilibili/mall/new/1`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `mall-new.ts`
- Source Module: `() => import('@/routes/bilibili/mall-new.ts')`

## Description
| 全部 | 手办 | 魔力赏 | 周边 | 游戏 |
| ---- | ---- | ------ | ---- | ---- |
| 0    | 1    | 7      | 3    | 6    |

## Parameters
- `category`: 分类，默认全部，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "| 全部 | 手办 | 魔力赏 | 周边 | 游戏 |\n| ---- | ---- | ------ | ---- | ---- |\n| 0    | 1    | 7      | 3    | 6    |",
  "example": "/bilibili/mall/new/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "mall-new.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/bilibili/mall-new.ts')",
  "name": "会员购新品上架",
  "parameters": {
    "category": "分类，默认全部，见下表"
  },
  "path": "/mall/new/:category?"
}
```
