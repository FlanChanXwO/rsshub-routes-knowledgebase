# 差评 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `chaping`
- Namespace Name: `差评`
- Route Path: `/news/:caty?`
- Route Name: `资讯`
- Example: `/chaping/news/15`
- URL: `chaping.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/chaping/news.ts')`

## Description
| 编号 | 分类       |
| ---- | ---------- |
| 15   | 直播       |
| 3    | 科技新鲜事 |
| 7    | 互联网槽点 |
| 5    | 趣味科技   |
| 6    | DEBUG TIME |
| 1    | 游戏       |
| 8    | 视频       |
| 9    | 公里每小时 |

## Parameters
- `caty`: 分类，默认为全部资讯


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
    "new-media"
  ],
  "description": "| 编号 | 分类       |\n| ---- | ---------- |\n| 15   | 直播       |\n| 3    | 科技新鲜事 |\n| 7    | 互联网槽点 |\n| 5    | 趣味科技   |\n| 6    | DEBUG TIME |\n| 1    | 游戏       |\n| 8    | 视频       |\n| 9    | 公里每小时 |",
  "example": "/chaping/news/15",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/chaping/news.ts')",
  "name": "资讯",
  "parameters": {
    "caty": "分类，默认为全部资讯"
  },
  "path": "/news/:caty?"
}
```
