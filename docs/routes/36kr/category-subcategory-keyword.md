# 36kr - 资讯, 快讯, 用户文章, 主题文章, 专题文章, 搜索文章, 搜索快讯

## Coverage
`index-only`

## Route
- Namespace: `36kr`
- Namespace Name: `36kr`
- Route Path: `/:category/:subCategory?/:keyword?`
- Route Name: `资讯, 快讯, 用户文章, 主题文章, 专题文章, 搜索文章, 搜索快讯`
- Example: `/36kr/newsflashes`
- URL: `36kr.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk, fashioncj`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/36kr/index.ts')`

## Description
| 最新资讯频道 | 快讯 | 推荐资讯 | 生活 | 房产 | 职场 | 搜索文章 | 搜索快讯 |
| ------- | -------- | -------- | -------- | -------- | --------| -------- | -------- |
| news | newsflashes | recommend | life | estate | workplace | search/articles/关键词 | search/articles/关键词 |

## Parameters
- `category`: 分类，必填项
- `subCategory`: 子分类，选填项，目的是为了兼容老逻辑
- `keyword`: 关键词，选填项，仅搜索文章/快讯时有效


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新资讯频道 | 快讯 | 推荐资讯 | 生活 | 房产 | 职场 | 搜索文章 | 搜索快讯 |\n| ------- | -------- | -------- | -------- | -------- | --------| -------- | -------- |\n| news | newsflashes | recommend | life | estate | workplace | search/articles/关键词 | search/articles/关键词 |",
  "example": "/36kr/newsflashes",
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "fashioncj"
  ],
  "module": "() => import('@/routes/36kr/index.ts')",
  "name": "资讯, 快讯, 用户文章, 主题文章, 专题文章, 搜索文章, 搜索快讯",
  "parameters": {
    "category": "分类，必填项",
    "keyword": "关键词，选填项，仅搜索文章/快讯时有效",
    "subCategory": "子分类，选填项，目的是为了兼容老逻辑"
  },
  "path": "/:category/:subCategory?/:keyword?"
}
```
