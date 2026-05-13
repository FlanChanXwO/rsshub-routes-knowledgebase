# 电玩巴士 TGBUS - 文章列表

## Coverage
`index-only`

## Route
- Namespace: `tgbus`
- Namespace Name: `电玩巴士 TGBUS`
- Route Path: `/list/:category`
- Route Name: `文章列表`
- Example: `/tgbus/list/news`
- URL: `tgbus.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `Xzonn`
- Source Location: `list.ts`
- Source Module: `() => import('@/routes/tgbus/list.ts')`

## Description
| 最新资讯 | 游戏评测 | 游戏视频 | 巴士首页特稿 | 硬件资讯 |
| -------- | -------- | -------- | ------------ | -------- |
| news     | review   | video    | special      | hardware |

## Parameters
- `category`: 列表分类，见下表


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.tgbus.com/list/:category/`
- `target`: `/list/:category`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 最新资讯 | 游戏评测 | 游戏视频 | 巴士首页特稿 | 硬件资讯 |\n| -------- | -------- | -------- | ------------ | -------- |\n| news     | review   | video    | special      | hardware |",
  "example": "/tgbus/list/news",
  "location": "list.ts",
  "maintainers": [
    "Xzonn"
  ],
  "module": "() => import('@/routes/tgbus/list.ts')",
  "name": "文章列表",
  "parameters": {
    "category": "列表分类，见下表"
  },
  "path": "/list/:category",
  "radar": [
    {
      "source": [
        "www.tgbus.com/list/:category/"
      ],
      "target": "/list/:category"
    }
  ]
}
```
