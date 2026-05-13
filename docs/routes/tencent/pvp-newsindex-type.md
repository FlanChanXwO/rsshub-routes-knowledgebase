# 腾讯 - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `tencent`
- Namespace Name: `腾讯`
- Route Path: `/pvp/newsindex/:type`
- Route Name: `新闻中心`
- Example: `/tencent/pvp/newsindex/all`
- URL: `tencent.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `Jeason0228, HenryQW`
- Source Location: `pvp/newsindex.ts`
- Source Module: `() => import('@/routes/tencent/pvp/newsindex.ts')`

## Description
| 全部 | 热门 | 新闻 | 公告 | 活动 | 赛事 | 优化 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| all  | rm   | xw   | gg   | hd   | ss   | yh   |

## Parameters
- `type`: 栏目分类，见下表


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
    "game"
  ],
  "description": "| 全部 | 热门 | 新闻 | 公告 | 活动 | 赛事 | 优化 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| all  | rm   | xw   | gg   | hd   | ss   | yh   |",
  "example": "/tencent/pvp/newsindex/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "pvp/newsindex.ts",
  "maintainers": [
    "Jeason0228",
    "HenryQW"
  ],
  "module": "() => import('@/routes/tencent/pvp/newsindex.ts')",
  "name": "新闻中心",
  "parameters": {
    "type": "栏目分类，见下表"
  },
  "path": "/pvp/newsindex/:type"
}
```
