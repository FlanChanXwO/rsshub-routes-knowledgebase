# 武汉大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `whu`
- Namespace Name: `武汉大学`
- Route Path: `/news/:category{.+}?`
- Route Name: `新闻网`
- Example: `/whu/news`
- URL: `cs.whu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `None`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/whu/news.ts')`

## Description
category 参数可选，范围如下:

| 新闻栏目 | 武大资讯 | 学术动态 | 珞珈影像 | 武大视频 |
| -------- | -------- | -------- | -------- | -------- |
| 参数     |  0 或 `wdzx/wdyw`  | 1 或 `kydt` | 2 或 `stkj/ljyx` | 3 或 `stkj/wdsp` |

此外 route 后可以加上 `?limit=n` 的查询参数，表示只获取前 n 条新闻；如果不指定默认为 10。

## Parameters
- `category`: 新闻栏目，可选


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "\ncategory 参数可选，范围如下:\n\n| 新闻栏目 | 武大资讯 | 学术动态 | 珞珈影像 | 武大视频 |\n| -------- | -------- | -------- | -------- | -------- |\n| 参数     |  0 或 `wdzx/wdyw`  | 1 或 `kydt` | 2 或 `stkj/ljyx` | 3 或 `stkj/wdsp` |\n\n此外 route 后可以加上 `?limit=n` 的查询参数，表示只获取前 n 条新闻；如果不指定默认为 10。\n",
  "example": "/whu/news",
  "location": "news.ts",
  "maintainers": [],
  "module": "() => import('@/routes/whu/news.ts')",
  "name": "新闻网",
  "parameters": {
    "category": "新闻栏目，可选"
  },
  "path": "/news/:category{.+}?"
}
```
