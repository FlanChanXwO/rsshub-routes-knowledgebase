# 得到 - 文章

## Coverage
`index-only`

## Route
- Namespace: `dedao`
- Namespace Name: `得到`
- Route Path: `/:category?`
- Route Name: `文章`
- Example: `/dedao`
- URL: `dedao.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/dedao/index.ts')`

## Description
| 新闻 | 人物故事 | 视频 |
| ---- | ---- | ---- |
| news | figure | video |

## Parameters
- `category`: 分类，见下表，默认为`news`


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
  "description": "| 新闻 | 人物故事 | 视频 |\n| ---- | ---- | ---- |\n| news | figure | video |",
  "example": "/dedao",
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/dedao/index.ts')",
  "name": "文章",
  "parameters": {
    "category": "分类，见下表，默认为`news`"
  },
  "path": "/:category?"
}
```
