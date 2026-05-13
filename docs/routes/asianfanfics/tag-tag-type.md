# Asianfanfics - 标签

## Coverage
`index-only`

## Route
- Namespace: `asianfanfics`
- Namespace Name: `Asianfanfics`
- Route Path: `/tag/:tag/:type`
- Route Name: `标签`
- Example: `/asianfanfics/tag/milklove/N`
- URL: `asianfanfics.com`
- Language: `en`
- Categories: `reading`
- Maintainers: `KazooTTT`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/asianfanfics/tag.ts')`

## Description
匹配asianfanfics标签，支持排序类型：
- L: Latest 最近更新
- N: Newest 最近发布
- O: Oldest 最早发布
- C: Completed 已完成
- OS: One Shots 短篇

## Parameters
- `tag`: 标签
- `type`: 排序类型


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.asianfanfics.com/browse/tag/:tag/:type`
- `target`: `/tag/:tag/:type`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "匹配asianfanfics标签，支持排序类型：\n- L: Latest 最近更新\n- N: Newest 最近发布\n- O: Oldest 最早发布\n- C: Completed 已完成\n- OS: One Shots 短篇\n",
  "example": "/asianfanfics/tag/milklove/N",
  "location": "tag.ts",
  "maintainers": [
    "KazooTTT"
  ],
  "module": "() => import('@/routes/asianfanfics/tag.ts')",
  "name": "标签",
  "parameters": {
    "tag": "标签",
    "type": "排序类型"
  },
  "path": "/tag/:tag/:type",
  "radar": [
    {
      "source": [
        "www.asianfanfics.com/browse/tag/:tag/:type"
      ],
      "target": "/tag/:tag/:type"
    }
  ]
}
```
